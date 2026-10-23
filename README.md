<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,55:450a0a,100:b91c1c&height=180&section=header&text=REACT%20NATIVE%20CALENDAR&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Custom%20date%20picker%20with%20react-native-calendars%20and%20Expo&descSize=16&descAlignY=58" width="100%" alt="React Native Calendar" />

<img src="https://img.shields.io/badge/React_Native-0d1117?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
<img src="https://img.shields.io/badge/Expo-0d1117?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
<img src="https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript" />
<img src="https://img.shields.io/badge/react--native--calendars-0d1117?style=for-the-badge&logo=googlecalendar&logoColor=F06543" alt="react-native-calendars" />
<img src="https://img.shields.io/badge/License-MIT-b91c1c?style=for-the-badge&labelColor=0d1117" alt="MIT License" />

</div>

<br />

## ▍ABOUT

A fully customized calendar screen built on top of [react-native-calendars](https://github.com/wix/react-native-calendars): dark theme, custom day cells, Brazilian Portuguese locale and a date picker that blocks past days.

## ▍FEATURES

- **Custom day component** with its own selected, today and disabled states
- **pt-BR locale:** month and weekday names in Portuguese
- **No past dates:** `minDate` set to today, extra days hidden
- **Dark theme** with a single accent color (`#F06543`)
- **Custom arrows** using Feather icons
- **Selected date readout** below the calendar

## ▍TECH STACK

| Layer | Tools |
| --- | --- |
| Core | React Native 0.76, Expo SDK 52, TypeScript |
| Calendar | react-native-calendars |
| Icons | @expo/vector-icons (Feather) |

## ▍GETTING STARTED

```bash
git clone https://github.com/williandeev/react-native-calendar.git
cd react-native-calendar
npm install
npx expo start
```

Press `a` for Android or `i` for iOS.

## ▍PROJECT STRUCTURE

```
src/
├── app/home/   # Calendar screen and styles
└── utils/      # pt-BR locale config for react-native-calendars
```

<br />

<div align="center">

<a href="https://github.com/williandeev"><img src="https://img.shields.io/badge/MADE_BY-WILLIAN_ROBSON-b91c1c?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" alt="Made by Willian Robson" /></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:b91c1c,45:450a0a,100:0d1117&height=100&section=footer" width="100%" alt="" />
