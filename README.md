## Vercel-CLI

#### Vercel CLI Install করুন
```bash
npm i -g vercel
```

#### Project Directory তে যান
```bash
cd your-project-folder
```

#### Vercel Project Link করুন
##### যদি এখনও link না করা থাকে:
```bash
vercel link
```
##### এটি আপনাকে Vercel account এ login করতে বলবে
##### এবং কোন project link করবেন তা select করতে হবে।

#### Environment Variables Pull করুন
##### সব environment variables download করতে:
```bash
vercel env pull
```
##### এটি .env.local file তৈরি করবে যাতে সব variables থাকবেে

