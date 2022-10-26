## Tailwind Starting Framework
This is a basic starting point to build your tailwindcss builds. Download the files and begin styling!

Tailwind Documentation: https://tailwindcss.com/docs/installation


**note:** If you leave your build (i.e. close the foldeer/IDE) you *might* need to add initialize --watch script. However, it should work without having to do this. 


The script
```npx
    npx tailwindcss -i ./tailwind.css -o ./css/styles.css --watch
```

This script scans your template files (html, js, etc) to see if any changes have been made. Once you saved your work, it runs the script, builds and deloys it. You'll be able to the changes in the browser. 
