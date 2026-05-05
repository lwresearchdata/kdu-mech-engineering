# 🎓 KDU Department of Mechanical Engineering – Student Directory

**General Sir John Kotelawala Defence University**  
BSc (Hons) Mechanical Engineering | BSc (Hons) Mechatronics Engineering  
Intakes 38 & 39

---

## 📁 Files in This Repository

```
kdu-mech-dept/
├── index.html          ← Main student directory page
├── admin.html          ← Admin panel (add/edit/delete students)
├── students_data.json  ← Student database (Intakes 38 & 39)
├── photos/             ← Student photos (optional folder)
│   ├── intake38/
│   └── intake39/
└── README.md
```

---

## 🚀 Step-by-Step: How to Create This on GitHub Pages

### STEP 1 – Create a GitHub Account
1. Go to https://github.com
2. Click **Sign up** and create a free account
3. Verify your email address

---

### STEP 2 – Create a New Repository
1. Click the **+** icon (top-right) → **New repository**
2. Fill in:
   - **Repository name:** `kdu-mech-engineering` (or any name you like)
   - **Description:** `KDU Department of Mechanical Engineering – Student Directory`
   - **Visibility:** ✅ Public (required for free GitHub Pages)
   - ✅ Check **Add a README file**
3. Click **Create repository**

---

### STEP 3 – Upload the Website Files
1. In your new repository, click **Add file** → **Upload files**
2. Upload these files (all at once by dragging):
   - `index.html`
   - `admin.html`
   - `students_data.json`
3. Scroll down, write a commit message: `Add KDU student directory website`
4. Click **Commit changes**

---

### STEP 4 – Enable GitHub Pages
1. Go to your repository → Click **⚙ Settings** (top menu)
2. Scroll down to **Pages** (left sidebar under "Code and automation")
3. Under **Source**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **Save**
5. Wait 1–2 minutes — GitHub will show you your live URL:
   ```
   https://YOUR-USERNAME.github.io/kdu-mech-engineering/
   ```

---

### STEP 5 – View Your Live Website
Open your browser and go to:
```
https://YOUR-USERNAME.github.io/kdu-mech-engineering/
```
- **Main directory:** `/index.html`
- **Admin panel:** `/admin.html`

---

## 📸 How to Add Student Photos

### Option A – Upload to GitHub (Recommended)
1. Create a folder `photos/` in your repository
2. Upload photos with filenames matching reg numbers (e.g., `D_ENG_21_0012_ME.jpg`)
3. In admin panel, use the photo URL: `photos/D_ENG_21_0012_ME.jpg`

### Option B – Use the Admin Panel Upload
1. Open `admin.html` on your website
2. Click **Add New Student** or **Edit** an existing student
3. Click the photo area to upload a JPG/PNG
4. The photo is stored in your browser (localStorage)
5. **Important:** After uploading photos, use **Export JSON** to download `students_data.json`
6. Upload the new `students_data.json` to GitHub to make photos permanent

---

## ➕ How to Add Future Intakes (e.g., Intake 40, 41...)

### Method 1 – Admin Panel (Easiest)
1. Open `https://YOUR-USERNAME.github.io/kdu-mech-engineering/admin.html`
2. In the **Add New Student** form, select **Intake 40** from the dropdown
3. Fill in Name, Reg. No., Programme, LinkedIn
4. Upload photo (optional)
5. Click **Save Student**
6. Repeat for each student
7. Click **Export JSON** to download the updated `students_data.json`
8. Upload to GitHub → changes appear on the website

### Method 2 – Edit JSON Directly
Add entries to `students_data.json` in this format:
```json
{
  "name": "ABC Perera",
  "regNo": "D/ENG/23/0001/ME",
  "linkedin": "https://linkedin.com/in/abc-perera",
  "program": "ME",
  "intake": 40,
  "photo": ""
}
```

---

## 🔄 How to Update the Website

1. Make changes via Admin Panel → Export JSON
2. Go to GitHub repository
3. Click on `students_data.json` → Click ✏️ edit icon
4. Paste new content → Commit changes
5. Website updates automatically within seconds

---

## 🎨 Website Features

| Feature | Description |
|---------|-------------|
| 🔍 Search | Search by name or registration number |
| 🗂 Filter by Intake | Filter Intake 38, 39, 40... |
| 🎓 Filter by Programme | BSc Mechanical / BSc Mechatronics |
| 👤 Profile Modal | Click any card to see full profile |
| 💼 LinkedIn | Direct LinkedIn profile links |
| 📸 Photos | Upload and display student photos |
| ⚙️ Admin Panel | Add, edit, delete students easily |
| 📤 Import/Export | Import/export JSON for bulk updates |

---

## 🛡 Admin Panel Notes

The admin panel (`admin.html`) saves data to **browser localStorage**.  
To make changes permanent and visible to everyone:
1. Make your changes in the admin panel
2. Click **⬇ Export JSON**  
3. Upload the downloaded `students_data.json` to GitHub
4. Everyone visiting the site now sees the updated data

---

## 📞 Support

Department of Mechanical Engineering  
General Sir John Kotelawala Defence University  
Ratmalana, Sri Lanka
