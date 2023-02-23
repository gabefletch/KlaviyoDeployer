<img src="https://user-images.githubusercontent.com/38300939/220998325-6958d659-1c4f-4c28-b820-1f448a91e60a.png" width=300>

A GitHub Pages solution to deploy [Klaviyo](https://klaviyo.com)-built signup pages. Made using basic HTML and JavaScript. 

JavaScript code is derived from Klaviyo itself.

KlaviyoDeployer is an opensource project by [Gabe Fletcher](https://dub.sh/gabe).

## Usage
### 1. Download the KlaviyoDeployer HTML File:
- Go to this repository's [Releases](https://github.com/gabefletch/KlaviyoDeployer/Releases) and click "index.html" under the latest release to download it.
### 2. Create your own repository:
- Click the "+" icon next to your profile picture in the upper-right of GitHub
- Click "New repository"
- Name it however you wish; we recommend something like "(YourNewsletterName)Deployer"
- Creating your own "readme.md" file is recommended but not absolutely required.
### 3. Edit "index.html" to load your Klaviyo page:
- Add the "index.html" file that you downloaded to your repository.
- While viewing the repository you just created, click "index.html" located above this "readme.md"

The index.html should appear as follows:
```
<script async type="text/javascript" src="https://static.klaviyo.com/onsite/js/klaviyo.js?company_id=YOUR_ID"></script>
```
- You'll need to find and replace "YOUR_ID" with your 6-digit Klaviyo form ID. 

### 4. Deploy with GitHub Pages
- Follow [these instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) to deploy your respository data to GitHub Pages, and in turn your Klaviyo form/landing page.

### 5. Test Your Deployment
- You can access your GitHub Pages deployment with the following syntax:

USERNAME.github.io/REPOSITORY_NAME

## How do I find my Klaviyo form ID?
- When logged in to Klaviyo, go to the landing page or form you wish to deploy with KlaviyoDeployer and you'll find your Form ID at the end of the URL.
- Copy this ID to replace "YOUR_ID" in your "index.html" file in your respository. 
