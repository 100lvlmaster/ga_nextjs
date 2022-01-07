# This nextjs app is an exmaple of implementing google analytics


## Installing the dependencies
```bash
npm run dev
or 
yarn
```

```bash
npm run dev
or 
yarn dev
```

1. Create an app on firebase https://firebase.google.com/
2. Make sure you're logged in with the same google account and then open https://analytics.google.com/analytics/web to see the google analytics dashboard
3. Select app on the Top-left second button
4. Setup stream if not already by going to the stream setup page entering the website name and url
5. Create a `pages/_document.tsx` file - refer code 
6. Create `.env.local` file and append the following key to it 

```bash
NEXT_PUBLIC_GOOGLE_ANALYTICS=<Your google tracking id>
 ```
 7. Add lib/ga folder to add custom events
 8. Make changes similar to `_app.tsx` to listen to route change events
 9. Refer `pages/index.tsx` to log custom events with params 
