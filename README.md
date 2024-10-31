# Immich
Self Hosted Image app with basic working setup and Remote Access with OpenVPN on router and Immich hosted on Fedora Linux Server 40.

## Router that I'm using is tp-link Archer AX53, but OpenVPN can be hosted on the server itself.
You can use the following article with the configuration from tp-link
https://www.tp-link.com/us/support/faq/1239/

This will allow you to connect to your homenetwork easy and securely allowing Immich to upload images when you are not in home.


<img width="1106" alt="Screenshot 2024-10-31 at 11 53 09" src="https://github.com/user-attachments/assets/1cdeabed-f7e2-49f2-8906-b61c7f213c14">

Immich developers have described the installation process pretty good. Just follow their article for Docker compose installation method.

https://immich.app/docs/install/docker-compose

I have attached the latest docker-compose.yml file and .env file, which is called immich.env here, but you will need to rename it to .env only.

You will need to populate your values which are left empty in the files and you are good to go. Just start the service with:

```
docker compose up -d
docker ps ///This will show you the running services
```
Immich needs docker and docker compose, just follow their article once again.

https://immich.app/docs/install/requirements

After it is up and running you can dowload the mobile app and log in.

Here is how it looks at the end.

