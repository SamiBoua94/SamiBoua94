I am looking for my first full-time job.
feel free to git clone my projects.

## How to add AI models to VS Code

You can use AI models inside VS Code through the **GitHub Copilot** extension.

### Steps

1. **Install the GitHub Copilot extension**
   - Open VS Code
   - Go to the Extensions panel (`Ctrl+Shift+X` / `Cmd+Shift+X`)
   - Search for **GitHub Copilot** and install it
   - Sign in with your GitHub account

2. **Choose a model in Copilot Chat**
   - Open the Copilot Chat panel (`Ctrl+Alt+I` / `Cmd+Alt+I`)
   - Click the **model picker** (dropdown at the top of the chat panel)
   - Select a model such as `GPT-4o`, `Claude`, `o1`, etc.

3. **Set a default model via settings**
   - Open Settings (`Ctrl+,` / `Cmd+,`) and search for `copilot chat model`
   - Or add the following to your `.vscode/settings.json`:

   ```json
   {
     "github.copilot.chat.defaultModel": "gpt-4o"
   }
   ```

   Available model values include: `gpt-4o`, `gpt-4o-mini`, `claude-3.5-sonnet`, `o1`, `o3-mini`.

4. **Switch models at any time**
   - In the Copilot Chat panel, use the model picker dropdown to switch between models on the fly.

> **Tip:** A `.vscode/settings.json` file is included in this repository as a starting point.
