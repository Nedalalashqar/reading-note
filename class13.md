# Local Storage

***Persistent local storage***

> Local Storage is designed to be a dependable, persistent store of data on a client.As client-side data - it is as persistent as any client side data, within the size limits that the browser implements. Users can delete it at any time, open it up in a text editor and edit etc. - just like ANY client side data.
> can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

> Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.

***INTRODUCING HTML5 STORAGE***

*What is HTML Web Storage?*
> With web storage, web applications can store data locally within the user's browser. Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

***HTML Web Storage Objects***

>HTML web storage provides two objects for storing data on the client:

* window.localStorage - stores data with no expiration date
* window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)

***The localStorage Object***
> The localStorage object stores the data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.

***The sessionStorage Object***

> The sessionStorage object is equal to the localStorage object, except that it stores the data for only one session. The data is deleted when the user closes the specific browser tab.

***TRACKING CHANGES TO THE HTML5 STORAGE AREA***

> he storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something

* QUOTA_EXCEEDED_ERR : is the exception that will get thrown if you exceed your storage quota of 5 megabytes. “No” is the answer to the next obvious question, “Can I ask the user for more storage space?” At time of writing , no browser supports any mechanism for web developers to request more storage space. Some browsers (like Opera) allow the user to control each site’s storage quota, but it is purely a user-initiated action, not something that you as a web developer can build into your web application.
