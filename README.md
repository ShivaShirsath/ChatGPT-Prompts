# ChatGPT-Prompts
Prompt Engineering from my imagination 😁


SVG generator with preview:
prompt: ```prompt
generate svg code for [INPUT]

show OUTPUT in markdown, without backticks, without "`"

Use this example :
! [](https://svg-cdn.vercel.app?svg=*)

replace * with svg code
  
I am providing INPUT
I want preview OUTPUT and it in this format '! [](https://svg-cdn.vercel.app?svg=*)'

Do you understand?
```
use:
   ```markdown
   Input: sin wave changing color
   ```
output:

   + ***
    Here is the SVG code for a sine wave changing color:

    ```
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 100">
      <defs>
        <linearGradient id="gradient">
          <stop offset="0%" stop-color="blue"/>
          <stop offset="50%" stop-color="green"/>
          <stop offset="100%" stop-color="red"/>
        </linearGradient>
      </defs>
      <path d="M 0 50 Q 25 40 50 50 Q 75 60 100 50 Q 125 40 150 50 Q 175 60 200 50 Q 225 40 250 50 Q 275 60 300 50 Q 325 40 350 50 Q 375 60 400 50 Q 425 40 450 50 Q 475 60 500 50" stroke="url(#gradient)" stroke-width="3" fill="none"/>
    </svg>
   ```

    And here is the output in markdown format:

    ![](https://svg-cdn.vercel.app?svg=%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20500%20100%22%3E%0A%20%20%3Cdefs%3E%0A%20%20%20%20%3ClinearGradient%20id%3D%22gradient%22%3E%0A%20%20%20%20%20%20%3Cstop%20offset%3D%220%25%22%20stop-color%3D%22blue%22%2F%3E%0A%20%20%20%20%20%20%3Cstop%20offset%3D%2250%25%22%20stop-color%3D%22green%22%2F%3E%0A%20%20%20%20%20%20%3Cstop%20offset%3D%22100%25%22%20stop-color%3D%22red%22%2F%3E%0A%20%20%20%20%3C%2FlinearGradient%3E%0A%20%20%3C%2Fdefs%3E%0A%20%20%3Cpath%20d%3D%22M%200%2050%20Q%2025%2040%2050%2050%20Q%2075%2060%20100%2050%20Q%20125%2040%20150%2050%20Q%20175%2060%20200%2050%20Q%20225%2040%20250%2050%20Q%20275%2060%20300%2050%20Q%20325%2040%20350%2050%20Q%20375%2060%20400%2050%20Q%20425%2040%20450%2050%20Q%20475%2060%20500%2050%22%20stroke%3D%22url(%23gradient)%22%20stroke-width%3D%223%22%20fill%3D%22none%22%2F%3E%0A%3C%2Fsvg%3E)
    ***
***
