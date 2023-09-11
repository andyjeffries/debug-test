# README

This is a repo to try to get <https://www.reddit.com/r/rails/comments/16faqk9/does_anyone_have_steps_for_vs_code_debugging_with/> working.

This is a freshly generated Rails app.

## Setup

I try running:

```
bundle exec rdbg --open --nonstop bin/rails s
```

In a terminal, set a breakpoint on users_controller.rb:24 and use "Attach with rdbg" in VS Code's Run and Debug section.

## Test results

I then create a user through the web interface (localhost:3000/users) but the debugger doesn't stop on the breakpoint.

The debug overlay bar has "Restart" and "Stop" enabled, and below "RUN AND DEBUG" is a blue bar that's about 3 characters wide animating from left to right constantly.
