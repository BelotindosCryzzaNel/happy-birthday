# A birthday surprise for Justin

This is a complete, dependency-free static website. Open `index.html` to preview it locally. It can be deployed free on Vercel without a build command or paid domain.

## Put the project on GitHub

1. Sign in at [github.com](https://github.com) and create a new repository named `happy-birthday`.
2. Choose **Add file → Upload files**.
3. Upload all files from this project folder, including the MP3. Keep `index.html`, `style.css`, `script.js`, `vercel.json`, and the MP3 in the repository's top level.
4. Select **Commit changes**.

## Deploy and get your link

1. Sign in at [vercel.com](https://vercel.com) using GitHub.
2. From the Vercel dashboard, choose **Add New → Project**, then import the `happy-birthday` repository.
3. Before deploying, set **Project Name** to `happy-birthday`.
4. Set **Framework Preset** to **Other**. Keep the root directory as `./`; leave **Build Command** blank and use `.` for **Output Directory** if Vercel asks for one.
5. Select **Deploy**. Vercel will show the public link after it finishes.

The link should be `https://happy-birthday.vercel.app` if that Vercel address is available. Vercel assigns `vercel.app` addresses on a first-come basis, so if it is taken, use a variation such as `happy-birthday-justin` and share the URL Vercel gives you. The project name can also be changed in Vercel's project settings.

When you edit the site later, upload and commit the changed files to GitHub. Vercel will deploy the update from that repository.

Background music uses the included karaoke/instrumental file `OTSO OTSO - bayani Agbayani (karaoke version) 🎶.mp3`. The site attempts playback from 00:13 on page load and continues across scene changes; the floating player can pause, mute, and adjust volume. Some browsers block audible autoplay until the visitor taps or clicks, so the site retries on that first interaction. Keep the MP3 in the project root when deploying.
