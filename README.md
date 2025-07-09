# Proteful
> [!NOTE]  
> This was a group project for Hack404. This fork has an updated description adapted from our [Devpost listing](https://devpost.com/software/temp-3m7t0b). 
> Checkout this video demo link for more info: https://youtu.be/Id7Y1Aai_jI?si=m-gE-EBukV11pKcm

## Description
Proteful is a mobile app that provides a real-time heatmap that indicates where dangerous protests are located. Through crowd-sourced reports, users can drop a “pin,” which consists of a radius, photo, and note to flag hazards such as police getting illegally violent, fights, outbreaks, etc. To keep users safe, Proteful uses these reports to help safely route users to their destination and provides AI summaries of hazards in their general location.

## Inspiration
Amid a surge in recent controversial events, protests have become increasingly frequent. However, they often escalate into violence, posing serious safety risks for individuals advocating for their rights and freedoms. Proteful’s goal is to make protesting a safer experience for those standing up for what they believe in.

## Tech Stack
Proteful is a mobile app built with Expo on top of React Native. Firebase allows us to store images and update the map in realtime with Realtime Database while abstracting complex backend logic for the mobile app. The Gemini API is used to provide AI summaries. An A* algorithm is used to help route users, as well as the OSRM API.

## Installation
1. Clone this repo
```bash
git clone https://github.com/LucasHJin/Proteful.git
cd Proteful
```
2. Install dependencies
```bash
npm install
```
3. Create a `.env` file with the following values
```bash
GEMINI_API_KEY=your_gemini_api_key
```
4. Run the following command and follow instructions for setting up the simulator on your computer or mobile device
```bash
npx expo start
```

## What's next for Proteful
We plan to launch and deploy it in the near future. Given the many ongoing controversies in today’s world, we believe Proteful has the potential to help many people. As mentioned earlier, its core mission is to make protesting a safer experience for those standing up for their beliefs. The sooner we release it, the sooner we can provide support and protection to those who need it most. Additionally, we plan to use NLP and web scraping of social platforms to autonomously update our app alongside crowdsourcing reports for more accuracy.
