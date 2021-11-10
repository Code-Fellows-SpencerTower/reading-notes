[THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS](http://diveinto.html5doctor.com/storage.html)

- cookies were invented early on and have drawbacks
  - included with every request, slow down apps
  - sometimes sent unencrypted

- HTML 5 storage
  - aka Web Storage / Local Storage / DOM Storage
  - stores key/value pairs locally, in the client browser
  - benefit is data not transmitted to the remote server
  - implemented natively

- access HTML 5 storage via `local storage` in global `window` object
- be sure browser supports HTML5 storage
- local storage can be treated as array
- can be cleared with js
- can add event listeners to track storage changes