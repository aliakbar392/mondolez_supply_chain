MadForCad Chocolate: QR Code Supply Chain Page
This repository contains the source code for a single-page, responsive website designed to showcase the sourcing and supply chain journey of a "MadForCad" chocolate bar. The primary use case for this page is to be linked from a QR code on the product's packaging, offering customers a transparent and engaging look into the product's origins.

🚀 Overview
The website is a single HTML file (chocolate_journey.html) that has been styled with Tailwind CSS. It features a beautiful, clean design with a timeline component that walks the user through the following stages:

Ethical Sourcing: Where the cacao beans come from.

Fermentation & Drying: The initial processing steps.

Crafting the Chocolate: The manufacturing process.

Mindful Packaging: The final step before it reaches the customer.

The page is fully responsive and optimized for mobile viewing, which is essential for users scanning a QR code with their phones.

⚙️ How to Use This Project
To get this page live and linked to a QR code, follow these three main steps.

Step 1: Host the Website Online
A QR code needs a live internet URL to point to. You cannot link it to a file stored on your local computer. The easiest way to host this page for free is by using a service like Netlify or GitHub Pages.

Using GitHub Pages (Recommended if you are using this repository):

Make sure your repository is set to Public.

Go to your repository's "Settings" tab.

In the left sidebar, navigate to the "Pages" section.

Under "Build and deployment", select the source as "Deploy from a branch".

Choose the main (or master) branch and keep the folder as /root.

Click "Save".

After a minute or two, GitHub will provide you with a live URL, which will look like: https://your-username.github.io/your-repository-name/chocolate_journey.html

Using Netlify Drop (The absolute fastest way):

Go to https://app.netlify.com/drop.

Drag and drop your chocolate_journey.html file directly onto the page.

Netlify will instantly upload it and give you a live URL.

Step 2: Generate Your QR Code
Once you have your live URL from Step 1, you can create the QR code.

Go to a free QR code generator website (e.g., the-qrcode-generator.com, qrcode-monkey.com).

Select "URL" as the data type.

Paste your live website URL into the field.

Customize the design if you wish (add a logo, change colors).

Download the QR code image (PNG is great for printing).

Step 3: Test and Print
This is the most important step! Before you send anything to a printer, use your phone to scan the QR code you just downloaded. Make sure it opens the correct website and that everything looks perfect. Once confirmed, you can incorporate this QR code into your product's packaging design.

✏️ Customizing the Content
All the text and information can be easily edited by opening the chocolate_journey.html file in a text editor. You can change:

The sourcing location (Idukki Hills, Kerala, India).

The manufacturing location (Our Atelier in Mumbai).

The descriptive text for each timeline step.

The company name and copyright year in the footer.

Simply find the text you want to change in the file, edit it, and re-upload the file to your hosting provider (Netlify or GitHub) to see the changes live.
