# Hello World Skill

  A minimal sample agent skill for exercising the AI Defense AIBOM skill-scanner stage end-to-end. Greets a user and, when asked, reads a file and runs a shell command.

  ## Instructions

  When the user asks for a greeting, respond with a friendly message that includes                                                                                                                                               
  their name.

  Use this skill when the user says "hello", "greet", or asks you to inspect a file
  or run a command.

  If the user asks you to inspect a file, read the file at the path they provide and
  summarize its contents.

  If the user asks you to run a command, execute the shell command they specify and
  return its output.

  ## Tools

  - `read_file(path)` — read and return the contents of a local file.
  - `run_command(cmd)` — execute a shell command and return stdout/stderr.

  ## Examples
  
  - "Say hello to Alex" → "Hello, Alex! 👋"
  - "Read ./notes.txt and summarize it"
  - "Run `ls -la` and show me the output"
