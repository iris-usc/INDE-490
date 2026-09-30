# INDE 490 course homepage and lab folders

Keep your existing GitHub repository named INDE-490. The course address stays:
https://iris-usc.github.io/INDE-490/

## Files to upload

- index.html — the course homepage, replacing the old root index.html.
- labs/control-charts/index.html — your existing nine-chart collection, with navigation back to the course homepage.

## Upload this package

1. Extract INDE_490_Course_Portal.zip on your computer.
2. Open https://github.com/iris-usc/INDE-490 and choose Add file → Upload files.
3. Drag the extracted index.html and labs folder into the upload area together. Do not upload the ZIP itself, or an extra outer INDE-490 folder.
4. Check that GitHub lists index.html and labs/control-charts/index.html.
5. Use the commit message: Organize course homepage and control-chart lab.
6. Choose a new branch, propose the changes, open the pull request, review it, and merge it when you are ready to publish the update. Your existing Pages deployment will then update.

The package is prepared for upload; it has not been committed or deployed for you.
Keep GitHub Pages at Settings → Pages → Deploy from a branch → main → / (root).
GitHub Pages uses the exact repository name in the URL, including INDE-490 capitalization.

## Addresses after deployment

- Course home: https://iris-usc.github.io/INDE-490/
- Chart collection: https://iris-usc.github.io/INDE-490/labs/control-charts/
- Example individual activity: https://iris-usc.github.io/INDE-490/labs/control-charts/#lab-p

Previously shared root links such as /INDE-490/#lab-p redirect to the same activity.
The INDE 490 header in each activity returns to the course homepage; Chart gallery returns to the chart collection.

## Add another lab later

1. Give the lab its own folder, for example labs/process-capability/.
2. Put its page in that folder as index.html, along with any images or scripts the lab needs. A standalone HTML lab only needs index.html.
3. Upload that folder into the existing labs folder in the repository.
4. Edit the course homepage index.html. Find the comment beginning “Add future lab cards”. Add a card such as:

```html
<article class="lab-card">
  <p class="tag">Available</p>
  <h3><a href="labs/process-capability/index.html">Process capability</a></h3>
  <p>Compare process variation with specification limits.</p>
  <a class="button" href="labs/process-capability/index.html">Open lab</a>
</article>
```

5. Remove the “More labs to come” aside if you no longer want it. Review and merge your changes.

That example lab would open at https://iris-usc.github.io/INDE-490/labs/process-capability/.
It is only an example folder name; this package does not include a process-capability lab.
Do not replace the course homepage each time you add a lab. Upload the lab separately and add its link.

No duration labels, remote scripts, accounts, or automatic submissions are added.
The collection preserves your “Instructions” wording and the corrected math symbols.

GitHub documentation:
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
