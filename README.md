# mycity-fighting-covid
To help support local responses to COVID-19, we're sharing code for a modular website design that you can adapt as you see fit for your local response. We are also assembling a collection of local response sites from around the world. Here are detailed instructions for anyone looking to create a website for your city.

### Before you start:

1. Determine what the needs are in your location. Every place is facing different challenges. Join up with your community response efforts and find out how you can make your site most useful, whether it's coordinating donations, distributing volunteer applications, or documenting ongoing efforts for others to learn from.
2. Please fill out [this google form](https://forms.gle/3wdkxzyGUNVjcgb7A) to let us know of your intentions to create a site, and for which city. We will maintain an "In progress" list at [earth.fightingcovid.net](https://earth.fightingcovid.net) so visitors can see whether their city is being covered.

### Using the template:

Our goal is simply to reduce the time it takes to get a working site up and running, so we are recommending modifying our template and hosting the site via GitHub pages for the shortest & smoothest out-the-door workflow while still allowing for minor to major customizations. That said, you're more than welcome to use whatever you'd like to build and host your site. If so, you can skip to the next section if you want to host via GitHub pages, or to the very last section if you just want us to add you to the collection.

1. Clone this repository to your computer. (In a terminal window, `git clone https://github.com/anthonyftwang/mycity-fighting-covid.git`)
2. Ideally, simply editing `index.html` to update links, text, and images should be sufficient for most and shouldn't take more than a few minutes. Change "mycity" to the name of your city/town/community, and add an appropriate header photo.
   1. Since the design is modular, you can delete sections you don't need or add new ones.
   2. (Optional - create/connect to a blog like WordPress, Jekyll, etc!)

### Hosting the site with GitHub Pages:

1. Create a GitHub account, if you don't already have one.
2. Create a new repository.
3. Make sure to rename the folder `mycity-fighting-covid` so it matches your repository name.
4. Push your code to GitHub:
   1. In a terminal window, `cd` into the website directory
   2. `git init`
   3. `git add .`
   4. `git commit -m "initial commit"`
   5. Copy the link to your GitHub repository, then `git remote add origin <git repo link>`
   6. `git push origin master`
5. Navigate to the **Settings** tab of your repository on GitHub. Scroll down to the GitHub pages section. Choose the branch `master` as the source, and the site should be published at `https://username.github.io/repository-name/`.

### Adding your site to earth.fightingcovid.net

Once your site is up, contact us at [opensource@fightingcovid.net](mailto:opensource@fightingcovid.net), and we'd be happy to add yours to [earth.fightingcovid.net](https://earth.fightingcovid.net). This lets visitors from around the world learn from each others' responses and will inspire even more people to join in their local efforts!

Additionally, if your site is live at `https://username.github.io/repository-name/` and you'd prefer a more relevant URL (or even just the latter), just let us know and we will help you get it working with something like `[mycity].fightingcovid.net`.
