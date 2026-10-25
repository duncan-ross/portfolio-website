# portfolio-website

My personal portfolio website: [duncanross.xyz](https://duncanross.xyz)

Plain static HTML/CSS in `public/`, hosted on Firebase Hosting. No build step.

- Preview locally: `python3 -m http.server 8080 --directory public`
- Add a project: copy the commented template at the top of the Projects list in `public/index.html`.
- Deploy: `firebase deploy --only hosting`
