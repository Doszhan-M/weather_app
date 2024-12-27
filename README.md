[![Netlify Status](https://api.netlify.com/api/v1/badges/dae9abe0-c800-4610-a85f-674adf78ea95/deploy-status)](https://app.netlify.com/sites/neon-weather/deploys)

# Weather Forecast
- Link to [Netlify](https://neon-weather.netlify.app/)

<br>

# Installation local
1. Install dependencies:
   ```bash
   npm install --legacy-peer-deps
   ```
2. Create a .env file in the root directory and add openweathermap token:
   ```bash
    WEATHER_TOKEN=Q9zy9Y1Ip8fLS3XVAlD
    NPM_FLAGS=--legacy-peer-deps
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Build for production:
   ```bash
   npm run build

5. Если перестал работать API: необходимо переподключить бесплатный тариф для openweathermap API v3.0


<br>


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
  WEATHER_TOKEN=Q9zy9Y1Ip8fLS3XVAlD
  NPM_FLAGS=--legacy-peer-deps
4. **Configure domain**:
- Site settings > Domain management.
  