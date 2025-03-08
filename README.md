# chrome-extension-enabler
This bookmarklet allows you to installed any chrome extension that is disabled by Chrome!

### How to Use:

1. **Create a Bookmark:**
   - Click the **"Add to Browser"** button below to quickly add this bookmarklet to your browser’s bookmarks bar.
   - Visit the [Chrome Web Store](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) extension page.
     ![image](https://github.com/user-attachments/assets/c3056281-492e-4893-87cd-eae70bb7b3b0)


   - Click the bookmark to enable the button.
   !![image](https://github.com/user-attachments/assets/eef8e697-b414-4dde-9ba8-da3525d09ccb)


---

### Manual Bookmark Creation:
If the "Add to Browser" button doesn’t work, follow these steps:

1. **Copy** the following JavaScript code:
    ```javascript
    javascript:!function t(){let e=document.querySelector(".VfPpkd-dgl2Hf-ppHlrf-sM5MNb button[disabled]");e?(e.removeAttribute("disabled"),e.setAttribute("enabled",""),console.log("Enabled!")):console.log("Failed!")}();
    ```
2. **Create a new bookmark** in your browser:
    - Right-click on the bookmarks bar and select **"Add Page..."** (or **"Add Bookmark"**).
    - Paste the JavaScript code into the **URL** field.
    - Name the bookmark (e.g., “Chrome Button Enabler”).
3. Visit the **Chrome Web Store extension page**, and click the bookmark to run the script.

---

### Contributing:
Feel free to contribute to this project! Fork the repository, make changes, and submit a pull request.

---

### License:
This project is open source and available under the MIT License.
