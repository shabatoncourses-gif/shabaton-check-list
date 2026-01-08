# התחלה מהירה 🚀

## שלב 1: הגדרת Firebase (5 דקות)

1. כנסו ל-https://console.firebase.google.com/
2. לחצו **Add project**
3. שם: `shabaton-checklist`
4. **Create project**
5. לחצו על האייקון `</>` (Web)
6. שם: `Shabaton Checklist`
7. **Register app**
8. **העתיקו את כל הקוד של firebaseConfig**
9. לחצו **Continue to console**
10. בתפריט: **Build** → **Firestore Database** → **Create database**
11. בחרו **Start in test mode** → **Enable**

## שלב 2: עדכון הקוד

1. פתחו את `index.html`
2. מצאו את השורות (קרוב לתחילת תגית ה-`<script>`):
```javascript
const firebaseConfig = {
    apiKey: "AIzaSyBXXXX...",
    ...
```
3. **החליפו** את כל האובייקט בקונפיגורציה שהעתקתם
4. שמרו

## שלב 3: העלאה ל-GitHub

1. צרו repository חדש בשם `shabaton-check-list`
2. העלו את 3 הקבצים: `index.html`, `README.md`, `.gitignore`
3. Settings → Pages → Source: `main` branch, `/ (root)` folder
4. Save

**זהו! האתר יהיה זמין תוך 2-3 דקות** 🎉

הכתובת: `https://shabatoncourses-gif.github.io/shabaton-check-list/`

---

לפרטים מלאים ראו: [README.md](README.md)
