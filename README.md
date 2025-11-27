

# NLPSI Workshop: Integrating NLP and Psychology to Study Social Interactions  

Repository for website: [https://nlpsi-workshop.github.io](https://nlpsi-workshop.github.io)  

## Editing  

The website is built automatically when you push or update the pages directly in GitHub. Always make edits in the `main` branch. The `gh-pages` branch is automatically generated and deployed.  

- To create a new page (e.g., Accepted Papers), create a `.md` file in the `_pages` folder.  
- To publish news updates or announcements, create a `.md` file as `_news/announcement_<n>.md`. Only the three latest news items will be displayed.  

## Archive Old Versions of the Workshop  

1. **Build the website locally.**  
    ```bash
    bundle install
    bundle exec jekyll build
    ```
   This creates a `_site` folder containing the static version of your active site.  

2. **Archive the site.**  
   Create a folder for the archive (e.g., `2025`) and copy the static files:  
    ```bash
    mkdir 2025
    cp -r _site/* 2025/
    ```
3. **Commit and push the changes.**  
   This makes the archived version available on GitHub Pages at:  
   [https://nlpsi-workshop.github.io/2025/](https://nlpsi-workshop.github.io/2025/)  

4. **List previous versions on the website.**  
  - Update `_pages/dropdown` (enable if not enabled).  
  - Add the link to the archived version.  

---
