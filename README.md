# Taiga-blueprint

Taiga is a project management platform for agile developers & designers and project managers who want a beautiful tool that makes work truly enjoyable.

The Taiga platform consists of three main components and each one has its own dependencies both at compile time and runtime:

- taiga-back (backend/api)
- taiga-front-dist (frontend)
- taiga-events (websockets gateway) (optional)

The login credentials are admin with password `123123`, please change after log in.
All information about Taiga and furhter configuration and usage you can find in maintaner's website: https://taiga.io/

This blueprint installs Taiga application on Subutai P2P Cloud. Learn more about Subutai here https://subutai.io

## Installation guide

1. Fill and set all variables

- PosgtreSQL database user's `taiga` password
- RabbitMQ message broker user's `taiga` password
- Secret Key for message broker
- Your domain or provided by Subutai Bazaar
- Environment name
- Container hostname
- Container type

![Screenshot from 2019-04-14 15-49-34](https://user-images.githubusercontent.com/33412152/56091184-2c891a00-5ecd-11e9-89af-a6df76ced6d1.png)

2. Choose peer where your blueprint will be installed
![Screenshot from 2019-04-14 15-09-42](https://user-images.githubusercontent.com/33412152/56090912-12017180-5eca-11e9-893d-7f7977e439c0.png)

3. Press `Finish` 
![Screenshot from 2019-04-14 15-10-02](https://user-images.githubusercontent.com/33412152/56090916-17f75280-5eca-11e9-9559-4670623cd3d2.png)

After installation finishes you can access your envrinment page by your domain name
![Screenshot from 2019-04-08 14-13-21](https://user-images.githubusercontent.com/33412152/56091198-517d8d00-5ecd-11e9-961a-964dfe3ffbe6.png)
