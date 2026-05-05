# ogtrailcafewebsite
I am creating a website for my cafe Og trail. It will be my first website development project using Claude AI. :) 

## 🗓️ Project Roadmap – Og Trail Café

### Week 1 – Setup & First Flask App
- [ ] Install Python 3, VS Code, Git  
- [ ] Create virtual environment and install Flask  
- [ ] Initialize Git repo  
- [ ] Build `/templates` and `/static` folders  
- [ ] Write `app.py` with “Home” route  
- [ ] Add `index.html`  
- [ ] Run server and confirm  
- [ ] Commit & push initial version  

### Week 2 – Add Pages & Routing
- [ ] Add `/menu` and `/gallery` routes  
- [ ] Create HTML templates and navigation  
- [ ] Test navigation flow  
- [ ] Commit & push changes  

### 🎨 Week 3 – Basic Styling & Layout
- [ ] Create `/static/styles.css` with brand colors and fonts  
- [ ] Design fixed header and footer for all pages  
- [ ] Add navigation bar linking Home / Menu / Gallery  
- [ ] Center page content and add background color or pattern  
- [ ] Include café logo or placeholder image in header  
- [ ] Ensure consistent layout across all templates  
- [ ] Add simple responsive styling for mobile  
- [ ] Commit & push (“Applied basic styling and navigation”)  

---

### 💾 Week 4 – Database Integration
- [ ] Install `flask_sqlalchemy`  
- [ ] Configure SQLite database URI in `app.py`  
- [ ] Create `MenuItem` model (id, name, price, category)  
- [ ] Run `db.create_all()` to generate `menu.db`  
- [ ] Insert sample menu data via Python shell  
- [ ] Update `menu.html` to render dynamic items with Jinja loop  
- [ ] Add “category” sections (Coffee, Snacks, etc.) if desired  
- [ ] Commit & push (“Database-driven menu implemented”)  

---

### 📊 Week 5 – Analytics Dashboard
- [ ] Add a new `/dashboard` route in `app.py`  
- [ ] Generate dummy sales or visitor data in Python  
- [ ] Use `matplotlib`, `plotly`, or `chart.js` to visualize data  
- [ ] Create `dashboard.html` to display charts and summaries  
- [ ] (Optional) Store analytics data in a table for future updates  
- [ ] Test dashboard rendering on local server  
- [ ] Commit & push (“Initial analytics dashboard added”)  

---

### 🚀 Week 6 – Collaboration, Documentation & Deployment
- [ ] Add collaborator for review and feedback  
- [ ] Use feature branches for new pages or dashboard tweaks  
- [ ] Perform at least one pull request review to simulate teamwork  
- [ ] Write a detailed `README.md` (intro, setup steps, screenshots, live demo link)  
- [ ] Generate final `requirements.txt` from environment  
- [ ] Deploy on Render, Railway, or PythonAnywhere  
- [ ] Verify all routes work on live site  
- [ ] Add deployment badge / link to README  
- [ ] Commit & push (“Final stable release deployed”)  

---

### 🧭 Post‑Project Enhancements (Optional)
- [ ] Add a contact or booking form (Flask‑Mail or API)  
- [ ] Embed Google Map for café location  
- [ ] Build admin panel to edit menu items dynamically  
- [ ] Expand dashboard with real data visualizations  
- [ ] Write a blog post about building the project  
