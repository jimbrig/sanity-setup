# Sanity Blogging Content Studio

- Hosted Studio: https://jimmys-sanitystudio.sanity.studio/desk

Repository housing infrastructure supporting my [Sanity.io](https://www.sanity.io/) CMS Setup.

Sanity Content Studio is an open source real-time content editing environment connected to the Sanity backend.

## Usage

- Project ID: `khs0dp2y` - needed for Content Lake access
- Database: `production`

```powershell
# install and initialize (follow prompts)
npm install -g @sanity/cli && sanity init

# navigate to project and explore schemas, etc.
cd sanity-setup && code-insiders .

# serve locally hosted studio
sanity start

# Launch browser to localhost port 3333
start http://localhost:3333

# deploy (defaults to sanity hosted server)
sanity deploy
```
## Documentation

- [Getting Started with Sanity CLI](https://www.sanity.io/docs/getting-started-with-sanity-cli)
- [Schema Types](https://www.sanity.io/docs/schema-types) ⭐
- [Sanity Studio](https://www.sanity.io/docs/sanity-studio)
- [Content Lake](https://www.sanity.io/docs/datastore)
- [Build with Sanity](https://www.sanity.io/docs/build-with-sanity)
- [Reference docs](https://www.sanity.io/docs/reference)

### Further Exploration

- [Read “getting started” in the docs](https://www.sanity.io/docs/introduction/getting-started?utm_source=readme)
- Check out the example frontend: [React/Next.js](https://github.com/sanity-io/tutorial-sanity-blog-react-next)
- [Read the blog post about this template](https://www.sanity.io/blog/build-your-own-blog-with-sanity-and-next-js?utm_source=readme)
- [Join the community Slack](https://slack.sanity.io/?utm_source=readme)
- [Extend and build plugins](https://www.sanity.io/docs/content-studio/extending?utm_source=readme)
