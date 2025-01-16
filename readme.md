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