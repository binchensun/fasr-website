# Preview in GitHub Codespaces (recommended)
1. Make a fork of [the main repository](https://github.com/ovro-eovsa/fasr-website/).  
2. Go to codespaces (https://github.com/codespaces) and create a new Codespace from your fork.  
3. Wait for the devcontainer to finish provisioning (it installs Hugo Extended and Go).  
4. In the Codespaces terminal, run:
   ```bash
   hugo server -D
   ```
5. Open the forwarded URL to preview the site. If `hugo` is missing, rebuild the container or run `.devcontainer/setup.sh` once.
6. Codespaces will pop up a forwarded port; click it to open the preview. Stop the server with `Ctrl+C` when done.

# Preview Locally
1. Clone your fork to your machine.  
2. Install [Hugo Extended](https://gohugo.io/getting-started/installing/) (0.111.3+ recommended).  
3. Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).  
4. From the project root:
   ```bash
   hugo server -D
   ```
5. Visit http://localhost:1313 (hot reload on save). Drop `-D` to hide drafts. Stop with `Ctrl+C` when done.
