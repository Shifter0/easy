# EasyMyBooking.com Website

This is a Next.js application for a travel and booking website.

## How to Run This Website on Your Server (e.g., BigRock VPS)

Follow these three steps after you have uploaded the code to your server. You will type these commands into your server's command line terminal (often using a tool called SSH).

---

### Step 1: Install Dependencies

This command downloads all the necessary libraries and packages that your website needs to function. You only need to run this command once when you first set up the project.

```bash
npm install
```

*(Wait for this command to finish completely before moving to the next step.)*

---

### Step 2: Build the Website

This command takes your code and prepares it for production. It creates a highly optimized version of your site to make it as fast as possible for your visitors. You must run this command before starting the site.

```bash
npm run build
```

*(Wait for the build process to complete.)*

---

### Step 3: Start the Website

This is the final command. It starts the web server, and your website will become live and accessible to anyone who visits your domain name.

```bash
npm run start
```

Your website should now be running! You can keep the terminal window open to see server logs.
