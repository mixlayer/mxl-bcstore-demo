# mxl-bcstore-demo

Mixlayer demo app that prematerializes products into a new GraphQL API at the edge.

### Getting Started

- Login to your Mixlayer account using `mxl login`.

- Create the app in your Mixlayer account

```bash
> git clone https://github.com/mixlayer/mxl-bcstore-demo
> cd mxl-bcstore-demo
> mxl init
```

- Set the necessary environment variables. You'll need the host name of your store and a Storefront API key for the BigCommerce GraphQL API.

```bash
> mxl env set BC_API_KEY <YOUR STOREFRONT API KEY>
> mxl env set BC_API_HOST <e.g. gottagofast.galaxy.lol>
```

- Deploy the app

```bash
> mxl refresh
```
