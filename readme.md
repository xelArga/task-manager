## Getting the Docker Container Started
1. Make sure you have docker installed on your computer
2. Navigate to the main folder
3. Run `docker compose up` in the terminal
4. To access the container shell,  run `docker exec -it <container-name> sh .`
5. When the container is running, website should be exposed at http://localhost:3000

More information on using Docker and the general files for setup can be found [here](https://docs.docker.com/manuals/)

## Next

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

## Windows - Code Changes Not Seen On Save
If you are having the issue where the folder isn't mounted and changes aren't reflected on save, the workaround I did is install WSL2 
(Windows Subsystem for Linux) on windows
1. [Install WSL](https://learn.microsoft.com/en-us/windows/wsl/install)
1. Get the vscode extension for WSL, instructions are [here](https://code.visualstudio.com/docs/remote/wsl)
1. Configure Docker Desktop for your WSL Distro, [docs here](https://docs.docker.com/desktop/features/wsl/#prerequisites)
1. Open vscode, and make a WSL2 connection, as seen in the above docs for the VScode extension. Navigate to the folder and open 
1. You may need to install git, if ubuntu based update system first then download `sudo apt update && sudo apt upgrade` then [install git](https://git-scm.com/downloads/linux)
1. You'll need ownership of docker to access it in the subsystem, so you will probably need to use `sudo docker compose up` to access it
