# Redirect

Skeleton of a Jekyll site that will turn all pages into redirects to another domain.

## How to use this

1. Generate a new repository from this one
2. Modify [`CNAME`](./CNAME) to contain the domain you are redirecting _from_.
3. Modify [`404.html`](./404.html) and replace the three instances of `example.com` with the domain you are redirecting _to_.
4. Enable Github Pages for your repository in the repository settings.
5. Follow the Github guidance for configuring your DNS to point to Github Pages.
