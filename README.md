# Habit 

habit is a bash script that works as a journal of your
habits/doings. You can visualize the weekly, monthly or
total progress of those habits/doings.

They are written to a file under $HOME/.habit/log which you
can access by doing `habit edit`.

Commands:
  help             Show help commands
  add              Adds an habit/doing entry
  edit             Opens the log file in the default $EDITOR
  goal             Adds an goal entry of an habit/doing
  list             Display the progress of the current week,
                   month or in total

## Motivation

Now a days there's a lot of tools to manage your life, it
gets kinda suffocating in ways that each app has it's own
workflow regarding tracking progress. One thing that I like
in this tools is the UI, and I definitely enjoy the ability
to visualize progress with graphs, and pretty colors.

My motivation is to write different *tiny* and *simple*
productivity tools that can sync with this gorgeous apps via
REST, like notion, for example. Plus I want to be easy to
integrate plugins using these commands on any text editor.

**NOTE**: I also had the intention to learn bash associative
arrays.
