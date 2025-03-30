# template-git-codespaces

# Homework 0

## Task #0 - Open this Project in a Codespace

This is simple. In fact, you've probably already done it. But if you come here via your repository and not the Classroom link, then click the Open in Codespaces button above. Alternatively, you can click the "<> Code ▼" button above right, select the Codespaces tab, and click "Create Codespace on Main".

## Task #1 - Create and Modify a Basic .NET Console App

In a subdirectory off of the root of this repository, add a new CONSOLE project in a directory called `hello-[firstname]` (e.g., for me the project would end up in the `/workspaces/homework-0-ptyork/hello-richard` directory). So either create the directory first or use the `-o` option in the `dotnet new` command as demonstrated in the lectures.

Now, use the editor to modify `Program.cs` to create what was likely one of your first C# programs ever. Use `Console.Write()`, `Console.ReadLine()`, and `Console.WriteLine()` to create the simple Q&A, asking the user for their name and simply greeting them as follows:

```
@rspencer ➜ /workspaces/homework-0-rspencer/hello-richard (main) $ dotnet run
Enter your name: Richard
Hello, Richard!
```

## Task #2 - Create and Test a Basic Razor Page Project

*Back in the root of your project workspace*, Create a new razor project using the appropriate `dotnet new` command(s). Place the project in a directory called `razor-[firstname]`. So for me this is `/workspaces/homework-0-rspencer/razor-richard`. Again, these are demonstrated in the lectures.

Now, modify the home page for the new project. I don't really care what you do, but minimally change the page title and modify the HTML content of your `Index.cshtml` page.

Test this in your browser by running the `dotnet watch` command and opening the appropriate link from the Ports tab as demonstrated in the video accompanying this exercise.

## Task #3 - Turn In Your Work!!!

When you are done, you must Commit and Sync your work to GitHub. As shown in the video accompanying this exercise, you must:

* Click the Source Control Tab
* Enter a Message (e.g., "ready to grade")
* Click the Commit & Sync button(s)
* Revisit the repository to insure that your files were submitted
