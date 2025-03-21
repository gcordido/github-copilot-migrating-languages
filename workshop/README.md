## Migrating a Python project to Rust

Let's go through some challenging requests for GitHub Copilot and address them
as they happen.

> [!NOTE]
> This repo is intended to give an introduction to various **GitHub Copilot** features, such as **Copilot Chat** and **inline chat**. Hence the step-by-step guides below contain the general description of what needs to be done, and Copilot Chat or inline chat can support you in generating the necessary commands.
>
> Each step (where applicable) also contains a `Cheatsheet` which can be used to validate the Copilot suggestion(s) against the correct command.
>
> 💡 Play around with different prompts and see how it affects the accuracy of the GitHub Copilot suggestions. For example, when using inline chat, you can use an additional prompt to refine the response without having to rewrite the whole prompt.

## Workshop features

In this workshop, you will be working with a Python project that has an HTTP
API. This project needs to be migrated and your main task will be to migrate
it over using the Rust programming language.
Here are some features:

1. Run the web application and open up the browser
1. Use the /docs endpoint in the running app to see the endpoints
1. All dependencies and libraries are pre-installed for Python
1. An initial test file in BASH is provided to validate correctness


## Start with the Python Project
Familiarize yourself with the project and its structure. The main file is
`main.py`, which contains the main logic of the application. Try to run it and see what the endpoints are.

### 1. Explore the project using agents

Use the `@workspace` agent to explain what is going on with this project.

- Open GitHub Copilot Chat and prefix your prompt with `@workspace`
- Ask questions like how to run the project

### 2. Determine the API endpoints

Launch your project and run the web application. Use GitHub Copilot chat with the `main.py` file open to provide context and ask about the endpoints.

- Try to run the project based on the suggestions of `@workspace` agent
- See all the possible endpoints and their requests types


### 3. Explore and run the shell tests

Tests are provided in the `tests` directory. Open the `test_endpoints.sh` file and use it to run tests. It requires the Python application to be running. Run the tests and inspect the output.

- Ask GitHub Copilot if more tests can be added
- If any tests are not currently passing, make sure they are updated

> [!NOTE]
> The application must be running for the tests to pass. If the app is not running you will get http errors.
> You can ask GitHub Copilot with the `@workspace` agent for help to run the application and gain insights on how to start it.

### 4. Strategize with GitHub Copilot
Now that you have a good understanding of the project, you can start strategizing with GitHub Copilot. Use the `@workspace` agent to ask questions about why the tests might be a good idea when rewriting the project in Rust.

- Ask GitHub Copilot to provide a summary of the tests
- Ask for suggestions on how to properly rewrite this project in Rust

> [!NOTE]
> Sometimes, GitHub Copilot may be eager to provide a lot of information including whole files with code. This is probably not what you want when trying to think about your options.
> Ensure you tell Copilot to avoid generating code when brainstorming and strategizing.

### 5. Identify missing tests

The tests are not complete and there are some missing cases. Use GitHub Copilot to identify the missing tests. This will help you get full coverage of the application before you start rewriting it in Rust.

- Open the test file and ask GitHub Copilot to identify missing tests
- Implement the missing tests
- Run the tests to ensure they are passing, fix any issues that arise


### 6. Create Rust scaffolding

Now that you have a good understanding of the project and its tests, you can start creating the Rust scaffolding. Use GitHub Copilot to help you with this. To simplify this process, assume the following guidelines for the Rust project:

- Use `actix-web` for the web framework
- Use `serde` for JSON serialization and deserialization

Ask GitHub Copilot to give you a step by step to start the project and the commands to run to get started. 

> [!NOTE]
> Why the dependencies might not fully work? Because LLMs sometimes don't have correct versions and tend to provide probabilistic results, not exact ones like a database would. Ensure that the versions used and installed will work and are correct. 


### 6. Create a single endpoint
Now that you have the scaffolding, you can start creating a single endpoint. Use Copilot to suggest the first pass for the `main.rs` file that will hold your first endpoint. Ensure that Copilot understands that it shouldn't generate the whole file, but only the main `/` endpoint. 

- Open the `main.rs` file and ask Copilot to generate *only* the `/` endpoint

>[!NOTE]
> You might be tempted to ask Copilot to generate the whole file, but you must validate each part as you make progress. It is easier to validate smaller parts than a whole file with multiple endpoints and logic.


### 7. Validate your first Rust endpoint

Now that you have the first endpoint in Rust, it is time to validate. This process of creating code and validating it is iterative and a solid practice when you need to develop a new project. It is even more crucial now that you are rewriting a project in a new language.

- Make sure the Python project is no longer running
- Ask Copilot help to run the Rust project in the same address and port as the Python project so that tests can run
- Run the tests to ensure they are passing, fix any issues that arise

### 8. Continue with all other endpoints

Use the same process as above to create all other endpoints. Add a single endpoint at a time, validate it, and run the tests.

For the JSON file, you will need to serialize and use `serde`. If you aren't familiar with this process you will have to rely on Copilot guidance. Ensure that you generate the smallest possible code and validate it immediately.

> [!TIP]
> Validating smaller parts of the code is easier than validating a whole file. It is also easier to debug smaller parts of the code. This is a good practice when using GitHub Copilot and it will help you in the long run.

### 9. Validate correctness 

Once you have all endpoiints in Rust with passing tests, then you can ask Copilot to do a review of the whole file. Identify potential caveats and issues or performance problems. For example, imagine if every endpoint is serializing the file every time. This is a performance issue and you can ask Copilot to identify it.

### 10. Add more endpoints with tests

Finally, you have a 1:1 mapping of the Python project to the Rust project. Now you can start adding more endpoints and tests. For example the `/countries/{country}` endpoint. This endpoint is not present in the Python project, but you can add it to the Rust project.

- With the `main.rs` file open, ask Copilot about other possible endpoints
- Open the `test_endpoints.sh` file and ask Copilot to add more tests for the new endpoints
- Run the tests to ensure they are passing, fix any issues that arise

### 11. Finalize the project with Rust tests
Now that you have all the endpoints and tests passing, you can now use Rust tests to validate the correctness. The shell tests were good enough to validate both Python and Rust by using the HTTP API. But now you can use Rust tests to validate the correctness of the Rust project using its own tests.

- Ask Copilot where you can add tests for the Rust project. Tests can go in the same `main.rs` file or in a separate file.
- Ask how to run the tests for validation
- Only add one test a time and validate it. This is the same process as before and will help you concentrate in one thing at a time.
