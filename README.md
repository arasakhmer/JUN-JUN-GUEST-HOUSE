/* normalize.css v8.0.1 | MIT License | github.com/necolas/normalize.css */button,hr,input{overflow:visible}progress,sub,sup{vertical-align:baseline}[type=checkbox],[type=radio],legend{box-sizing:border-box;padding:0}html{line-height:1.15;-webkit-text-size-adjust:100%}body{margin:0}details,main{display:block}h1{font-size:2em;margin:.67em 0}hr{box-sizing:content-box;height:0}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}a{background-color:transparent}abbr[title]{border-bottom:none;text-decoration:underline;text-decoration:underline dotted}b,strong{font-weight:bolder}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative}sub{bottom:-.25em}sup{top:-.5em}img{border-style:none}button,input,optgroup,select,textarea{font-family:inherit;font-size:100%;line-height:1.15;margin:0}button,select{text-transform:none}[type=button],[type=reset],[type=submit],button{-webkit-appearance:button}[type=button]::-moz-focus-inner,[type=reset]::-moz-focus-inner,[type=submit]::-moz-focus-inner,button::-moz-focus-inner{border-style:none;padding:0}[type=button]:-moz-focusring,[type=reset]:-moz-focusring,[type=submit]:-moz-focusring,button:-moz-focusring{outline:ButtonText dotted 1px}fieldset{padding:.35em .75em .625em}legend{color:inherit;display:table;max-width:100%;white-space:normal}textarea{overflow:auto}[type=number]::-webkit-inner-spin-button,[type=number]::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}[type=search]::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}[hidden],template{display:none}



/* Variables */
html {
  --grey: #e7e7e7;
  --gray: var(--grey);
  --blue: #0072B9;
  --pink: #D60087;
  --yellow: #ffc600;
  --black: #2e2e2e;
  --red: #c73737;
  --green: #61e846;
  --text-shadow: 2px 2px 0 rgba(0,0,0,0.2);
  --box-shadow: 0 0 5px 5px rgba(0,0,0,0.2);
  font-size: 62.5%;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

body {
  font-size: 2rem;
  line-height: 1.5;
  background-color: var(--blue);
  background-image: url("data:image/svg+xml,%3Csvg width='20' height='100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M0 21.184c.13.357.264.72.402 1.088l.661 1.768C4.653 33.64 6 39.647 6 50c0 10.271-1.222 15.362-4.928 24.629-.383.955-.74 1.869-1.072 2.75v6.225c.73-2.51 1.691-5.139 2.928-8.233C6.722 65.888 8 60.562 8 50c0-10.626-1.397-16.855-5.063-26.66l-.662-1.767C1.352 19.098.601 16.913 0 14.85v6.335zm20 0C17.108 13.258 16 8.077 16 0h2c0 5.744.574 9.951 2 14.85v6.334zm0 56.195c-2.966 7.86-4 13.123-4 22.621h2c0-6.842.542-11.386 2-16.396v-6.225zM6 0c0 8.44 1.21 13.718 4.402 22.272l.661 1.768C14.653 33.64 16 39.647 16 50c0 10.271-1.222 15.362-4.928 24.629C7.278 84.112 6 89.438 6 100h2c0-10.271 1.222-15.362 4.928-24.629C16.722 65.888 18 60.562 18 50c0-10.626-1.397-16.855-5.063-26.66l-.662-1.767C9.16 13.223 8 8.163 8 0H6z' fill='%23fff' fill-rule='nonzero' fill-opacity='.1' opacity='.349'/%3E%3C/svg%3E%0A");
  background-size: 15px;
}


/* Table Styles */

table {
  border-radius: 5px;
  overflow: hidden;
  margin-bottom: 2rem;
  border-collapse: collapse;
}

td, th {
  border: 1px solid var(--grey);
  padding: 0.5rem;
}


/* Helper Divs */

.wrapper {
  max-width: 1000px;
  margin: 4rem auto;
  padding: 2rem;
  background: white;
}

.box, .wrapper {
  box-shadow: 0 0 3px 5px rgba(0,0,0,0.08653);
}
a {
  color: var(--blue);
  text-decoration-color: var(--yellow);
}


a.button, button, input[type="button"] {
  color: white;
  background: var(--pink);
  padding: 1rem;
  border: 0;
  border: 2px solid transparent;
  text-decoration: none;
  font-weight: 600;
  font-size:2rem;
}

:focus {
  outline-color: var(--pink);
}

fieldset {
  border: 1px solid black;
}

input:not([type="checkbox"]):not([type="radio"]), textarea, select {
  display: block;
  padding: 1rem;
  border: 1px solid var(--grey);
}

.success {
  border: 1px solid red;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  color: white;
  margin-top: 0;
  line-height: 1;
  text-shadow: var(--text-shadow);
}
.wrapper h1,
.wrapper h2,
.wrapper h3,
.wrapper h4,
.wrapper h5,
.wrapper h6 {
  color: var(--black);
  text-shadow: none;
}

