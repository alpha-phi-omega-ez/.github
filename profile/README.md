# Alpha Phi Omega, Epsilon Zeta Chapter
Alpha Phi Omega is an all-inclusive community service fraternity. The Epsilon Zeta Chapter has been on the campus of Rensselaer Polytechnic Institute for 76 years, helping serve the RPI students, Troy NY, and Capital Region communities. In our campus office we run the lost and found, store backtests for students to reference, and loan chargers and calculators to students.

### Connect with us:
- Email: contact@apoez.org
- Website: [apoez.org](https://apoez.org)
- Facebook: [Alpha Phi Omega - Epsilon Zeta](https://www.facebook.com/APOatRPI)
- Instagram: [@apoez_rpi](https://www.instagram.com/apoez_rpi/)

##  On Github we are currently working on:
- :computer: [New Website!](https://apoez.org)
  - [NextUI Frontend](https://github.com/alpha-phi-omega-ez/frontend), Creating a brand new website from scratch using NextUI
  - The backend is made up of a [FastAPI backend](https://github.com/alpha-phi-omega-ez/backend) with MongoDB handling Lost and Found, Loanertech, and Backtest CRUD tasks.
  - We also have scheduled scripts to [manage backtests](https://github.com/alpha-phi-omega-ez/backtest-compilation) that read a folder and file structure of our backtest drive and update our MongoDB collections to reflect the up-to-date data. Some one-time scripts were used to transfer old data from our old MySQL setup and [transfer](https://github.com/alpha-phi-omega-ez/transfer) to our new MongoDB infrastructure.
- [Discord bot](https://github.com/alpha-phi-omega-ez/photo-discord-bot) that uploads event photos from Discord threads to our Google Drive for permanent storage. Using Discord.py for the discord bot and Google's API to create folders and upload files. It downloads images and uploads them through threads and asynchronous programming to prevent long blocking times on the Discord bot.
- BMoC is a fundraiser we run alongside RPI student government elections that has candidates running to be the Biggest Meme on Campus and getting votes via donations to their charities of choice
  - [Spring 2024 website](https://github.com/alpha-phi-omega-ez/BMoC) built with assistance from Wix
