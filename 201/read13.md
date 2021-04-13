## Local Storage 
- Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.
- HTML5 Storage is based on named key/value pairs, the key is a string, but the value can be any data type(supported by JavaScript).
- We can trap the storage event in order to keep track programmatically of when the storage area changes.
- HTML web storage provides two objects for storing data on the client:
window. localStorage - stores data with no expiration date.
window. sessionStorage - stores data for one session (data is lost when the browser tab is closed).
- To use localStorage in our web applications; we can use: setItem(), getItem(), removeItem(), clear() .