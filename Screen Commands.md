Screen Commands

Screen commands to help you become an expert:

1. **Creating and Managing Sessions**:
   - **screen**: Start a new session.
   - **screen -S [session name]**: Start a new session with a specific name.
   - **screen -ls**: List all active screen sessions.
   - **screen -r [session name]**: Reattach to a detached session.
   - **screen -d [session name]**: Detach from a session without closing it.

2. **Working with Windows**:
   - **Ctrl+a, c**: Create a new window.
   - **Ctrl+a, n**: Switch to the next window.
   - **Ctrl+a, p**: Switch to the previous window.
   - **Ctrl+a, [0-9]**: Switch to a specific window by number.
   - **Ctrl+a, A**: Rename the current window.
   - **Ctrl+a, "**: List all windows for selection.
   - **Ctrl+a, d**: Detach from the current window.

3. **Window Splitting**:
   - **Ctrl+a, |**: Split the current window vertically.
   - **Ctrl+a, S**: Split the current window horizontally.
   - **Ctrl+a, Tab**: Switch focus between window splits.
   - **Ctrl+a, X**: Remove the current region (split).

4. **Copying and Scrolling**:
   - **Ctrl+a, [**: Enter copy/scrollback mode.
   - **Ctrl+b**: Enter copy/scrollback mode (alternative binding).
   - **Spacebar**: Start selection (copy) in copy mode.
   - **Enter**: Copy the selected text to the clipboard.
   - **Ctrl+a, ]**: Paste the clipboard content.
   - **Ctrl+a, :**: Enter command mode (for advanced scrolling and searching).

5. **Session Management**:
   - **Ctrl+a, :** + `quit` or `exit`: Close the current session.
   - **Ctrl+a, :** + `sessionname [name]**: Rename the current session.
   - **Ctrl+a, :** + `kill` or `kill [session name]**: Terminate a session.

6. **Configuration and Customization**:
   - **Ctrl+a, :** + `source ~/.screenrc`: Reload the screen configuration from the `.screenrc` file.
   - **Ctrl+a, :** + `caption always "%{= wk}[ %n %t %w ]"`: Customize the session caption.

These commands cover the essential functionalities of Screen, allowing you to create, manage, and navigate multiple terminal sessions efficiently. As you gain experience, you can explore more advanced features and customizations offered by Screen to further enhance your productivity.