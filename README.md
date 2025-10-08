# What Happend 💬✨

![What Happend Banner](https://github.com/user-attachments/assets/6cc9dfea-da1f-4351-945c-6d770174df0d)

## 🚀 TL;DR  
*Your crush just texted you. You've typed 47 different responses and deleted them all. This app is your therapy.*

## 🤔 What Actually Is This?

We've all been there. You get a text message and suddenly forget how to human. Should you be funny? Flirty? Professional? Your brain short-circuits, your palms get sweaty, and you're googling "how to respond to 'hey' without seeming desperate."

**What Happend** (yes, we intentionally misspelled "Happened" because we're quirky like that) is an AI-powered text message response generator that takes your overthinking to the next level—by outsourcing it to Google's Gemini AI. Simply paste any text message, choose your vibe, and let artificial intelligence do the social anxiety for you.

Perfect for:
- 💘 Overthinkers who've rewritten "sounds good" 18 times
- 🤡 People who want to be funny but aren't
- 😏 Those who think they're smooth but need AI confirmation
- 🧠 Anyone who wants to psychoanalyze a two-word text

## 🛠️ Features

- **Summary Mode** - Because sometimes "k" needs a dissertation-length interpretation
- **Funny Mode** - Generate replies so hilarious your keyboard will judge you for not thinking of them first
- **Flirty Mode** - AI-crafted pickup lines that are somehow less cringe than what you'd type yourself
- **Analysis Mode** - Overanalyze messages like a detective investigating a crime scene (spoiler: "haha" with no punctuation means they hate you)
- **Beautiful UI** - Gorgeous flickering grid background so you look professional while panicking about a text
- **Expandable Tabs** - Smooth animations that make your indecisiveness look intentional
- **Real-time Processing** - Get AI responses faster than you can type "is this too much?"

## 🧑‍💻 How To Install?

### Prerequisites
- **Node.js** (>= 20.0.0) - Because we're fancy
- **npm** (>= 10.0.0) or **yarn** (>= 1.22.0)
- **A Gemini API Key** - Get one from [Google AI Studio](https://makersuite.google.com/app/apikey)
- **Crippling text anxiety** (optional but recommended)

### Frontend Setup

1. **Clone this repository of desperation:**
   ```bash
   git clone https://github.com/RealNickey/What-Happend.git
   cd What-Happend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```

4. **Open your browser:**
   Navigate to `http://localhost:5173` and witness your salvation

### Backend Setup (The Brain)

1. **Navigate to backend folder:**
   ```bash
   cd backend
   ```

2. **Install backend dependencies:**
   ```bash
   npm install
   ```

3. **Create a `.env` file with your secrets:**
   ```bash
   echo "GEMINI_API_KEY=your_api_key_here" > .env
   echo "PORT=3000" >> .env
   ```

4. **Start the backend server:**
   ```bash
   npm start
   ```
   
   Or for development with hot reload:
   ```bash
   npm run dev
   ```

5. **Configure frontend API URL:**
   Create a `.env` file in the root directory:
   ```bash
   VITE_API_URL=http://localhost:3000
   ```

## 🎯 How To Use?

1. Open the app (you got this far, congrats!)
2. Paste the text message that's causing you existential dread
3. Click one of the four magic buttons:
   - 📝 **Summary** - "Basically they said..."
   - 😂 **Funny** - Make 'em laugh (hopefully)
   - 💕 **Flirty** - Slide into their DMs with AI confidence
   - 🧠 **Analysis** - Overthink it scientifically
4. Copy the AI-generated response
5. Stare at it for another 10 minutes before sending
6. Repeat when they respond

## 🎨 Tech Stack (The Fancy Stuff)

<p>
   <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" height="30px">
   <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" height="30px">
   <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" height="30px">
   <img src="https://img.shields.io/badge/shadcn%2Fui-000?style=for-the-badge&logo=shadcnui&logoColor=white" alt="ShadcnUI" height="30px">
   <img src="https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" height="30px">
   <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" height="30px">
   <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white" alt="Google Gemini AI" height="30px">
</p>

- **React** - For building the UI of your anxiety
- **Vite** - Lightning-fast builds (unlike your response time)
- **Tailwind CSS** - Making panic attacks look aesthetic since 2019
- **ShadcnUI** - Pre-built components so we didn't have to think too hard
- **Framer Motion** - Smooth animations that hide your existential dread
- **Express.js** - Backend that handles your overthinking
- **Google Gemini AI** - The real MVP doing all the heavy lifting
- **Lucide Icons** - Pretty icons for pretty people

## 📁 Project Structure

```
What-Happend/
├── backend/                 # Where the AI magic happens
│   ├── server.js           # Express server with Gemini API integration
│   ├── package.json        # Backend dependencies
│   └── .env               # Your precious API key (don't commit this!)
├── src/
│   ├── App.jsx            # Main component (your anxiety hub)
│   ├── components/
│   │   └── ui/            # Beautiful components for beautiful disasters
│   │       ├── expandable-tabs.jsx  # The four horsemen of texting
│   │       ├── result-modal.jsx     # Where AI saves your life
│   │       ├── textarea.jsx         # Where you paste your panic
│   │       └── flickering-grid.jsx  # Aesthetic background vibes
│   ├── lib/
│   │   ├── api.js         # Frontend API calls to backend
│   │   └── utils.js       # Utility functions (the unsung heroes)
│   └── main.jsx           # App entry point
├── public/                # Static assets
├── package.json           # Frontend dependencies
└── README.md             # You are here!
```

## 🤝 Contributing

Found a bug? Want to add a "Passive-Aggressive" mode? Contributions are welcome!

1. Fork this repo
2. Create your feature branch (`git checkout -b feature/even-more-overthinking`)
3. Commit your changes (`git commit -m 'Add sarcastic mode'`)
4. Push to the branch (`git push origin feature/even-more-overthinking`)
5. Open a Pull Request
6. Overthink whether your PR description is good enough

## ⚠️ Disclaimer

- This app uses AI. AI can be wrong. Don't blame us if it generates "hey bestie 💅✨" when you meant to be professional.
- Not responsible for relationships ruined by algorithmic flirting
- The AI doesn't actually know what they meant—it's just really good at pretending
- If you're using Analysis mode on "k", you might need actual therapy, not AI

## 🐛 Known Issues (aka Features)

- Sometimes generates responses that are *too* smooth (prepare for high expectations)
- May cause you to question whether AI is better at texting than you (it probably is)
- No "Desperately Professional" mode yet (coming soon™)
- The typo in "Happend" is intentional and we're sticking to it

## 📝 License

This project is open source and available under the MIT License. Use it responsibly. Or don't. We're not your mom.

## 🙏 Credits

Built with love, anxiety, and way too much caffeine by someone who definitely needed this app themselves.

Special thanks to:
- Google Gemini AI for being smarter than all of us
- Every person who's ever stared at their phone for 20 minutes deciding how to respond
- You, for reading this far instead of just checking the code

## 💬 Final Words

Remember: If you're using an AI to help you text, you're not alone. You're just efficiently outsourcing your social anxiety to cloud computing. And that's beautiful.

Now go forth and text with confidence! (Or at least with AI-generated confidence!)

---

<p align="center">
   Made with ❤️ and 😰 by <a href="https://github.com/RealNickey">RealNickey</a>
</p>

<p align="center">
   <i>What Happend? We helped you respond, that's what.</i>
</p>
