# Payload Bulk Upload bug reproduction

This repository is to demonstrate a bug in the Bulk Upload feature of Payload, referenced in [this issue](https://github.com/payloadcms/payload/issues/11868).

## Setup

The bug is encountered in the default website template, which can be created using `pnpx create-payload-app my-project -t website` and selecting `postgres` as the adapter.

If you want to use this repositiory instead, it is unchanged from the default website template, except for this README file. Setup steps for this repo are as follows:

1. Have postgres v17 installed and running
1. Clone this repo.
1. `pnpm install && pnpm dev` to install dependencies and start the dev server
1. open `http://localhost:3000` to open the app in your browser
1. Login to the admin panel and proceed to the Media collection.
1. Follow the steps in the [issue](https://github.com/payloadcms/payload/issues/11868) to reproduce the bug.
