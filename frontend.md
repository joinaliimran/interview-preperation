What is useMemo?
Use Memo
useMemo is used to increase the performance of a React application. Basically, when the component is re-rendered the function defined in it is called every time. So, to eliminate the calling of the function we use useMemo. useMemo basically caches the value and returns the same value every time and when some change happens in the dependency array it is called and returns a new value based on the computation. We cannot use useMemo every time because it uses space for caching the value and also we can face some performance issues. useMemo is also used for referential equality problems. Because arrays, objects, and function references are again created when the component is re-rendered and if their value is declared in a useEffect dependency array then the useEffect function will be called whenever the component is re-rendered.

Example
const returnedValue = useMemo(() => {
someFunction();
}, [value]);

Referential Equality Solution
useMemo is used to increase the performance of a React application.
Basically, when the component is re-rendered the function defined in it is
called every time. So, to eliminate the calling of the function we use
useMemo. useMemo basically caches the value and returns the same
value every time and when some change happens in the dependency
array it is called and returns a new value based on the computation. We
cannot use useMemo every time because it uses space for caching the
value and also we can face some performance issues. useMemo is also
used for referential equality problems. Because arrays, objects, and
function references are again created when the component is re-rendered
and if their value is declared in a useEffect dependency array then the
useEffect function will be called whenever the component is re-rendered.
Example
const returnedValue = useMemo(() => {
someFunction();
}, [value]);
Referential Equality Solution

const obj = useMemo(() => {
return { fruit: 'apple' };
}, []);

What is the concept of NEXT JS head?
How Next JS improves the SEO?
