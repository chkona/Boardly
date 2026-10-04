# ბორდლი (Boardly) — Phase 1 პროტოტიპი

ქართული ონლაინ სამაგიდო თამაშების პლატფორმის ვიზუალური დემო.
პროექტი ერთი ფაილია: `index.html`. ინსტალაცია არ სჭირდება.

## ლოკალურად გაშვება

**ვარიანტი 1 (უმარტივესი):** ორჯერ დააწკაპუნეთ `index.html`-ზე — გაიხსნება ბრაუზერში.

**ვარიანტი 2 (ლოკალური სერვერი):** გახსენით ტერმინალი ამ საქაღალდეში და გაუშვით:

    python3 -m http.server 8000

შემდეგ ბრაუზერში გახსენით http://localhost:8000

## GitHub-ზე ატვირთვა

1. შექმენით ანგარიში: https://github.com
2. დააჭირეთ **New repository**, სახელად ჩაწერეთ `boardly`, დააჭირეთ **Create repository**.
3. დააინსტალირეთ Git: https://git-scm.com
4. ტერმინალში, ამ საქაღალდეში:

       git init
       git add .
       git commit -m "ბორდლი Phase 1 პროტოტიპი"
       git branch -M main
       git remote add origin https://github.com/თქვენი-მომხმარებელი/boardly.git
       git push -u origin main

(თუ Git პაროლს მოგთხოვთ, GitHub-ზე გამოიყენეთ Personal Access Token პაროლის ნაცვლად.)

**ტერმინალის გარეშე:** GitHub-ის რეპოზიტორიის გვერდზე დააჭირეთ **Add file → Upload files** და ჩააგდეთ `index.html`, `README.md`, `.gitignore`.

## უფასო ონლაინ გამოქვეყნება (GitHub Pages)

1. რეპოზიტორიაში: **Settings → Pages**.
2. **Source:** Deploy from a branch → **main** / (root) → **Save**.
3. 1–2 წუთში საიტი გაიხსნება: `https://თქვენი-მომხმარებელი.github.io/boardly/`

## შემდეგი ეტაპები

- დარჩენილი გვერდები და 9 თამაშის მაგიდა
- გადასვლა Next.js + TypeScript + Tailwind არქიტექტურაზე
- რეალური მულტიპლეიერი, ბაზა და ხმოვანი ჩატი (WebRTC)
