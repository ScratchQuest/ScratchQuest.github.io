JOURNEY TO SCRATCH — SIMPLE SITE

How to use (no coding):
1) Copy ALL of these files into your GitHub repo folder named YOURUSERNAME.github.io
   - Put them next to .git and .gitattributes (not inside .git)
2) Open GitHub Desktop:
   - You should see the files under "Changes"
   - Summary: First upload
   - Click "Commit to main"
   - Click "Publish repository" (Public)
3) Turn on GitHub Pages:
   - On GitHub.com open your repo -> Settings -> Pages
   - Source: Deploy from a branch
   - Branch: main  / (root)   -> Save
4) Wait ~2 minutes. Your link will be: https://YOURUSERNAME.github.io

How to add an entry later:
- Open data.js in any text editor
- Copy/paste another object in the ENTRIES list, e.g.

  {
    date: "Aug 09, 2025",
    day: "Day 2",
    title: "Wedge practice, distance control",
    summary: "50-yard ladder drill, 120 swings. 20x from 10–30 ft putting.",
    category: "Practice",
    tags: ["wedges","distance"],
    metrics: [{label:"Swings", value:"120"}]
  }

- Save the file, then in GitHub Desktop: Commit to main -> Push origin
- The site updates automatically.
