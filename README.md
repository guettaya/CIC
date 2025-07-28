# Hello Tempest Throne - Tech Team

Here are some commands:

## To run rCTF locally:

```bash
export NODE_OPTIONS=--openssl-legacy-provider
Use the yarn command to install.

Sometimes you need to increase the number of files watched:

echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
Then run:
yarn dev
You will see the URL to open the site.

To change the frontend pages:
Go to:
cd rctf/frontend/client/src/routes
You will find all the pages there.
