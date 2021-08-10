# Local Storage

Client-side storage works on similar principles, but has different uses. It consists of JavaScript APIs that allow you to store data on the client (i.e. on the user's machine) and then retrieve it when needed. This has many distinct uses, such as:

Personalizing site preferences (e.g. showing a user's choice of custom widgets, color scheme, or font size).
Persisting previous site activity (e.g. storing the contents of a shopping cart from a previous session, remembering if a user was previously logged in).
Saving data and assets locally so a site will be quicker (and potentially less expensive) to download, or be usable without a network connection.
Saving web application generated documents locally for use offline
Often client-side and server-side storage are used together. For example, you could download a batch of music files (perhaps used by a web game or music player application), store them inside a client-side database, and play them as needed. The user would only have to download the music files once — on subsequent visits they would be retrieved from the database instead.
![](https://i.stack.imgur.com/cI5kT.jpg)


The localStorage read-only property of the window interface allows you to access a Storage object for the Document's origin; the stored data is saved across browser sessions.

localStorage is similar to sessionStorage, except that while localStorage data has no expiration time, sessionStorage data gets cleared when the page session ends — that is, when the page is closed. (localStorage data for a document loaded in a "private browsing" or "incognito" session is cleared when the last "private" tab is closed.)

### Syntax 
  ##### myStorage = window.localStorage;

  ##### The following snippet accesses the current domain's local Storage object and adds a data item to it using Storage.setItem().

###### localStorage.setItem('myCat', 'Tom');
 ##### reading the localStorage item is as follows:

###### const cat = localStorage.getItem('myCat');

##### removing the localStorage item is as follows:

###### localStorage.removeItem('myCat');
 ##### removing all the localStorage items is as follows:

###### localStorage.clear();


