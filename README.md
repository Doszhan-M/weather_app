# JS-React F2 
## Weather Forecast

npm install --legacy-peer-deps

https://doszhan-m.github.io/weather_forecast/

Если перестал работать API:необходимо переподключить бесплатный тариф для openweathermap API v3.0



# Installation on Netlify
1. **Set Up a New Site on Netlify**:
- Log in to your [Netlify dashboard](https://app.netlify.com/).
- Click **Add new site** > **Import an existing project**.
- Choose the **GitHub repository**.

2. **Configure the Build Settings**:
```bash
Site name https://neon-weather.netlify.app
base directory: /
package directory: /
build command: npm install --legacy-peer-deps && npm run build
publish directory: /dist
functions directory: /
```

3. **Add Environment Variables**:
- Go to the **Environment Variables** section in the build settings.
- Add the environment variable for the Telegram bot token:
  ```
  TELEGRAM_TOKEN=9774699703:MBUx7liQHbpN7XKSpa5aMWC05mcFDMsiH14
4. **Configure domain**:
- Site settings > Domain management.