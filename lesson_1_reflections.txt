How did viewing a diff between two versions of a file help you see the bug that
was introduced?


    It allows you to quickly and easily see both files which allows you to spot differences quickly. If you had to look in one file and then open the other you could forget what you had in the first file and it could lead to ever more mistakes.


How could having easy access to the entire history of a file make you a more
efficient programmer in the long term?

    There's many ways this would be helpfull. You would be able to look back on these files later on if you ever run across a problem that you had in a program before. This would allow you to see how you fixed the problem. Also it would allow you to experiment with the code without the fear of completely losing your progress on the program you're working on.

What do you think are the pros and cons of manually choosing when to create a
commit, like you do in Git, vs having versions automatically saved, like Google
docs does?

    The pros will be having every commit make sense to the users. It wouldn't allow changes to happen mid line and you are able to manually tag each change in the commit. The con is user error and forgetting to commit or not publishing commits at the right time.

Why do you think some version control systems, like Git, allow saving multiple
files in one commit, while others, like Google Docs, treat each file separately?

    Because in programming one logical change comes with multiple file change, so that one can save entire working project rather than single individual file.

How can you use the commands git log and git diff to view the history of files?

    git log shows all the commits, or versions, of my files that I have ever saved (or that the person who created the histroy ever saved). I can use that to see the message for each commit, and get a quick idea of the sorts of changes that have been made.
    To dig deeper into any commit, I can use git diff to compare that commit to the previous commit and see exactly what changes were introduced.

How might using version control make you more confident to make changes that
could break something?

    You can try changing any critical features, since you can always revert back to the point when those were working correctly. If you find something is not working, you can git log, and try the  previous versions untill you find the one which works, and make diff of the last one that worked correctly and the commit following it. That result would show where and how the bug was introduced.

Now that you have your workspace set up, what do you want to try using Git for?

    I used Git to keep track of many of the UE documents write with Markdown.
