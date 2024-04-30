# Setup Repository
Create a repo in GitHub, it must be named "<your github username>.github.io"

# Setup Automatic deployment
Go to settings > Pages > Build and Deployment
and change source to "GitHub Actions"
 
# Local Development
[Install Hugo](https://gohugo.io/installation/)

make a 'themes' directory in the repository route
```bash
mkdir themes
```
make a submodule to the theme:
```bash
cd themes
git submodule add https://github.com/bjacquemet/personal-web.git
```

### Adding/Changing content
Make changes to `config.toml`
Add images and things to `static`
Make changes to the blog, portfolio and about sections in the `content` folder

See the [Theme's readme](https://github.com/bjacquemet/personal-web.git) for further details

### Run server locally
```bash
hugo server -D
```