# Vibe-Coding-Essentials

Post Need to read to create essential discussion before coding a full stack

https://www.deeplearning.ai/the-batch/the-ai-engineering-skills-map-in-detail-software-engineering-fundamentals?utm_content=385231196&utm_medium=social&utm_source=twitter&hss_channel=tw-992153930095251456



## Trying to find issues

https://github.com/usestrix/strix


 Claude skills install kar lena:
1. Taste skill: ye premium references se asli design taste uthata hai aur tera UI mockup vibe kholi app jaisa lagna band ho jata hai.
2. Web design guidelines: ye tera code Vercel ke latest design rules pe audit karta hai aur ship karne se pehle weak points flag kar deta hai.
3. Awesome design: ye tera AI ko poora design system pakda deta hai. Typography, spacing, buttons, sab kuch ready hota hai. Image to code, ye kisi bhi design reference ko usable code bana deta hai, bina detail khoaye.
4. Playwright CLI: ye Claude ko browser kholne deta hai. Wo apna banaya hua app khud screenshot leta hai aur error to usse pehle hi pakad leta hai.

your app is painfully slow and you don't even realise it yet. Here are the five things it probably forgot to do. Don't worry, all of these are vibe codable changes. You just needed to know to ask for them.
1. Your JSON is going over the wire uncompressed, which just makes everybody wait longer for everything your backend server responds with.
2. Your app is writing new rows to your database one at a time, which increases overhead for no reason. This isn't something that you would notice at one user but at 1,000 users your app would feel like molasses.
3. You have a single dependency bottleneck. To identify this you can audit your roundtrip latency and break it down into specific network events. If one action is taking 90% of the roundtrip time, that is your bottleneck.
4. Every single action the user takes waits on the response from the backend before updating anything in the user interface.
5. Your frontend web server is rebuilding HTML for every visitor that loads up the site.
