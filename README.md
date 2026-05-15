## How organization profiles work

1. Must create `.github` repo like this one
2. The repo can:
   1. Contain:
      1. `/assets` folder (if you put the images in the `profile` folder and the `README.md` in the `/profile` folder references it direct then that will work). I put more files in `/assets` so I used it to hold all of my images but's not required
      2. `/profile` folder that holds a `README.md` <-- Required (both folder and file)
3. Commit your `.github` repo and merge until `main` branch (may work with any other branch but have not tested it)
4. The repo must be public
5. The other repos in the org do not have to be public
