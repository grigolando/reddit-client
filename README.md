# Reddit Client App 📱🤖

ეს არის Reddit-ის გამარტივებული ვერსია (Client Application), რომელიც აგებულია **React**-ისა და **Redux Toolkit**-ის ბაზაზე. აპლიკაცია ინტეგრირდება Reddit-ის ოფიციალურ API-სთან, რაც მომხმარებელს საშუალებას აძლევს დაათვალიეროს პოპულარული პოსტები, მოძებნოს სასურველი ინფორმაცია და წაიკითხოს კომენტარები.

პროექტის ცოცხალი ვერსია (Live Demo): [ჩასვი შენი დეპლოის ბმული, მაგ. https://your-reddit-app.netlify.app]

---

## 🎨 Wireframes (ინტერფეისის ჩანახატები)

> [აქ ჩასვი შენი Figma-ს ვიზუალი ან სკრინშოტი, მაგალითად: `![Wireframe](./assets/wireframe.png)`]
*აპლიკაციის დიზაინი სრულად ადაპტირებულია როგორც დესკტოპისთვის, ასევე მობილური მოწყობილობებისთვის (Mobile-First approach).*

---

## 🛠️ გამოყენებული ტექნოლოგიები (Technologies Used)

*   **Frontend:** React (Hooks, Functional Components)
*   **State Management:** Redux Toolkit (Slices, Async Thunks)
*   **Routing / View:** React Router (ან Component-based Modal View)
*   **Styling & Animations:** CSS Modules / Styled Components / Framer Motion
*   **Testing:** Jest & React Testing Library (ან Enzyme)
*   **API:** Reddit JSON API
*   **Performance Optimization:** Lighthouse Audit (90+ ქულა SEO, Accessibility და Best Practices კატეგორიებში)

---

## ✨ ფუნქციები (Features)

*   **საწყისი ხედი (Initial View):** აპლიკაციაში შესვლისას მომხმარებელი ავტომატურად ხედავს პოპულარულ (Trending) პოსტებს.
*   **ძებნა (Search):** საძიებო ველის მეშვეობით მონაცემების დინამიური გაფილტვრა საკვანძო სიტყვების მიხედვით.
*   **კატეგორიები (Subreddits Filter):** პოსტების გაფილტვრა წინასწარ განსაზღვრული კატეგორიების (მაგ. r/gaming, r/reactjs, r/movies) მიხედვით.
*   **დეტალური ხედი (Detailed View):** პოსტზე დაწკაპუნებისას იხსნება მოდალური ფანჯარა ან ახალი გვერდი, სადაც ჩანს პოსტის სრული აღწერა და მომხმარებლების კომენტარები.
*   **შეცდომების მართვა (Error Handling):** აპლიკაციას აქვს Error State — ინტერნეტის გათიშვის ან API-ს ხარვეზის შემთხვევაში, მომხმარებელს ეძლევა შეცდომიდან გამოსვლისა და გვერდის გადატვირთვის შესაძლებლობა.
*   **ანიმაციები:** ინტერფეისი გამდიდრებულია ფლუიდური ტრანზიციებით უკეთესი User Experience-ისთვის.
