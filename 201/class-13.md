# Read: Class 13

Recognizing what local storage can and cannot store ensures that we make informed decisions when implementing data storage solutions in web applications. Additionally, comprehending the significance of data type conversion before storage is fundamental for effective data manipulation and retrieval, which is central to web development tasks. 

[Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

1. Why would a developer use local storage for a web application?

Developers use local storage in web applications for its advantages, including persistent data storage, improved performance, offline capabilities, enhanced user experience, reduced server load, security, privacy, and simplicity in implementation. It's a convenient way to store data on the user's device, improving application functionality and performance.

2. What information should not be stored in local storage?

Sensitive and confidential information, such as user credentials, personal data, session tokens, and financial details, should not be stored in local storage due to security and privacy risks.

3. Local storage can store what type of data? How would you convert it to that type before storing?

Local storage can store data in the form of strings. To store other data types, such as objects or numbers, you need to convert them to strings before storing. You can use methods like `JSON.stringify()` for objects or simply use the string representation of the data for numbers. When retrieving the data from local storage, you would need to convert it back to its original data type using methods like `JSON.parse()` for objects or parsing for numbers.
