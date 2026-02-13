# ❤️ Happy Valentine L

A beautiful, interactive, and romantic web experience designed as a special Valentine's Day gift. This project features a multi-step interactive flow that leads to a stunning 3D Dome Gallery of memories.

## ✨ Features

- **Love Mode Toggle**: A premium glassmorphic switch to set the mood.
- **Interactive Tic-Tac-Toe**: A "rigged" game where winning reveals a heart-shaped surprise.
- **Love Meter**: An accurate SVG-based gauge that fills up to 100%.
- **Typewriter Message**: A classic typewriter animation for a personalized Valentine's greeting.
- **3D Dome Gallery**: A fully interactive 3D sphere gallery that displays your favorite photos.
- **Background Music**: Autoplaying and looping romantic music (`pretty.mp3`).
- **Premium UI**: Crafted with Tailwind CSS, Framer Motion, and Playfair Display typography.

## 🚀 Getting Started

Follow these steps to get a copy of the project up and running on your local machine.

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DzarelDeveloper/Valentine-Days.git
   cd Valentine-Days
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   Navigate to [http://localhost:3000](http://localhost:3000) to see the result.

## 📸 Customization

### Changing Photos
Put your images in the `public/` folder and name them `1.jpeg`, `2.jpeg`, up to `15.jpeg`. If you have more or fewer photos, update the `userImages` array in `app/page.tsx`.

### Changing Music
Replace the `public/pretty.mp3` file with your preferred romantic track (keep the filename or update it in `app/page.tsx`).

### Changing the Message
You can edit the typewriter text in `components/InteractionFlow.tsx` by searching for the `TypewriterStep` component.

## 🌐 Hosting & Deployment

The easiest way to deploy this project is using the **Vercel Platform**.

### Deploy to Vercel (Recommended)
1. Push your code to a GitHub, GitLab, or Bitbucket repository.
2. Go to [Vercel](https://vercel.com/) and create a new project.
3. Import your repository.
4. Vercel will automatically detect Next.js and deploy your project.

### Manual Build
To create an optimized production build:
```bash
npm run build
npm run start
```

## 🛠️ Built With
- [Next.js 15](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Lucide React](https://lucide.dev/)

---
Made with ❤️ by DzarelDeveloper
