First Next.js app:

instead of using useState to have a state and useEffect to call the Api request after the component is mounted -
creating a function, getServerSideProps, which contains the request and return the data as a props while allow
to rename the data with a key - "todos".
then I pass it as a destructured prop and render it conditionally if the length is more then zero.
This makes the app work faster without those two hooks and lines of code, also the SEO is better while the app's
content appears immediately.
