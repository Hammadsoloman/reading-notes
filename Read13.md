# Read 12

**I Learned From This Article:**

* userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.
(Trusted domains, such as intranet sites, can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.) 
IE does not present any form of permissions dialog, and there is no allowance for increasing the amount of storage available.

* “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper,
but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer
to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named,

* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with
the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers,
or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you
will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

* If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage
event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, 
because nothing actually changed in the storage area.
