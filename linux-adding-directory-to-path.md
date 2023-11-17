# Adding a Directory to `$PATH` in Linux

When you install a tool, it's essential to ensure its executable is in the system's `$PATH` so that you can run the tool from any location in the terminal. This guide covers both temporary and permanent solutions for adding a directory to the `$PATH`.

## Temporary Solution (for the current session)

1. **Identify the Directory:**
   - Find the directory where the executable is located. For example, let's assume it's in `/path/to/your/tool`.

2. **Add to `$PATH`:**
   - Open a terminal and use the following command to add the directory to the `$PATH` for the current session:

     ```bash
     export PATH="/path/to/your/tool:$PATH"
     ```

   - This ensures the tool is available for the duration of the current terminal session.

3. **Verify:**
   - Verify that the tool is now accessible:

     ```bash
     yourtoolcommand
     ```

## Permanent Solution (for future sessions)

1. **Identify the Shell Configuration File:**
   - Identify the shell configuration file for your shell. Common ones include `.bashrc`, `.bash_profile`, `.zshrc`, or `.profile`. The exact file depends on your shell (Bash, Zsh, etc.) and your system.

2. **Open the Configuration File:**
   - Use a text editor to open the configuration file. For example, with Bash:

     ```bash
     nano ~/.bashrc
     ```

3. **Add to `$PATH`:**
   - Add the following line to the end of the file, replacing `/path/to/your/tool` with the actual path:

     ```bash
     export PATH="/path/to/your/tool:$PATH"
     ```

   - Save and exit the editor.

4. **Load the Changes:**
   - Either start a new terminal session or use the following command to apply the changes to the current session:

     ```bash
     source ~/.bashrc
     ```

5. **Verify:**
   - Verify that the tool is now accessible:

     ```bash
     yourtoolcommand
     ```

Now, the tool's directory is permanently added to your `$PATH`, ensuring you can run the tool from any location in the terminal.
