The Global Object
Value Properties
NaN
Infinity
undefined
Function Properties
eval(x)
parseInt(string, radix)
parseFloat(string)
isNaN(number)
isFinite(number)
decodeURI(encodedURI)
decodeURIComponent(encodedURIComponent)
encodeURI(uri)
encodeURIComponent(uriComponent)
Constructor Properties
Object
Function
Array
String
Boolean
Number
Date
RegExp
Error
EvalError
RangeError
ReferenceError
SyntaxError
TypeError
URIError
Other Properties
Math
JSON
The Object Object
Object Constructor
Function Properties
getPrototypeOf(O)
getOwnPropertyDescriptor(O, P)
getOwnPropertyNames(O)
create(O [, Properties])
defineProperty(O, P, Attributes)
defineProperties(O, Properties)
keys(O)
seal(O)
isSealed(O)
freeze(O)
isFrozen(O)
preventExtensions(O)
isExtensible(O)
Object Prototype
Function Properties
toString()
toLocaleString()
valueOf()
hasOwnProperty(V)
isPrototypeOf(V)
propertyIsEnumerable(V)
Function Objects
Function Prototype
Function Properties
toString()
apply(thisArg, argArray)
call(thisArg [, arg1 [, arg2, ...]])
bind((thisArg [, arg1 [, arg2, …]])
Array Objects
Array Prototype Object
Function Properties
toString()
toLocaleString()
concat([item1 [, item2 [, ...]]])
join(separator)
find(callbackfn [, thisArg]) // ECMAScript 6: Added in Qt 5.9
findIndex(callbackfn [, thisArg]) // ECMAScript 6: Added in Qt 5.9
pop()
push([item1 [, item2 [, ...]]])
reverse()
shift()
slice(start, end)
sort(comparefn)
splice(start, deleteCount[, item1 [, item2 [, ...]]])
unshift([item1 [, item2 [, ...]]])
indexOf(searchElement [, fromIndex])
lastIndexOf(searchElement [, fromIndex])
every(callbackfn [, thisArg])
some(callbackfn [, thisArg])
forEach(callbackfn [, thisArg])
map(callbackfn [, thisArg])
filter(callbackfn [, thisArg])
reduce(callbackfn [, initialValue])
reduceRight(callbackfn [, initialValue])
String Objects
String Prototype Object
Function Properties
toString()
valueOf()
charAt(pos)
charCodeAt(pos)
concat([string1 [, string2 [, ...]]])
endsWith(searchString [, endPosition ]) // ECMAScript 6: Added in Qt 5.8
includes(searchString [, position ]) // ECMAScript 6: Added in 5.8
indexOf(searchString ,position)
lastIndexOf(searchString, position)
localeCompare(that)
match(regexp)
repeat(count) // ECMAScript 6: Added in Qt 5.9
replace(searchValue, replaceValue)
search(regexp)
slice(start, end)
split(separator, limit)
startsWith(searchString [, position ]) // ECMAScript 6: Added in Qt 5.8
substring(start, end)
toLowerCase()
toLocaleLowerCase()
toUpperCase()
toLocaleUpperCase()
trim()
Additionally, the QML engine adds the following functions to the String prototype:

arg()
Boolean Objects
Boolean Prototype Object
Function Properties
toString()
valueOf()
Number Objects
Number Prototype Object
Function Properties
toString(radix)
toLocaleString()
toFixed(fractionDigits)
toExponential(fractionDigits)
toPrecision(precision)
Additionally, the QML engine adds the following functions to the Number prototype:

fromLocaleString(locale, number)
toLocaleCurrencyString(locale, symbol)
toLocaleString(locale, format, precision)
The Number Object
Value Properties
NaN
NEGATIVE_INFINITY
POSITIVE_INFINITY
MAX_VALUE
MIN_VALUE
EPSILON // ECMAScript 6: Added in Qt 5.8
Function Properties
isFinite(x) // ECMAScript 6: Added in Qt 5.8
isNaN(x) // ECMAScript 6: Added in Qt 5.8
The Math Object
Value Properties
E
LN10
LN2
LOG2E
LOG10E
PI
SQRT1_2
SQRT2
Function Properties
abs(x)
acos(x)
asin(x)
atan(x)
atan2(y, x)
ceil(x)
cos(x)
exp(x)
floor(x)
log(x)
max([value1 [, value2 [, ...]]])
min([value1 [, value2 [, ...]]])
pow(x, y)
random()
round(x)
sign(x) // ECMAScript 6: Added in Qt 5.8
sin(x)
sqrt(x)
tan(x)
Date Objects
Date Prototype Object
Function Properties
toString()
toDateString()
toTimeString()
toLocaleString()
toLocaleDateString()
toLocaleTimeString()
valueOf()
getTime()
getFullYear()
getUTCFullYear()
getMonth()
getUTCMonth()
getDate()
getUTCDate()
getDay()
getUTCDay()
getHours()
getUTCHours()
getMinutes()
getUTCMinutes()
getSeconds()
getUTCSeconds()
getMilliseconds()
getUTCMilliseconds()
getTimeZoneOffset()
setTime(time)
setMilliseconds(ms)
setUTCMilliseconds(ms)
setSeconds(sec [, ms])
setUTCSeconds(sec [, ms])
setMinutes(min [, sec [, ms]])
setUTCMinutes(min [, sec [, ms]])
setHours(hour [, min [, sec [, ms]]])
setUTCHours(hour [, min [, sec [, ms]]])
setDate(date)
setUTCDate(date)
setMonth(month [, date])
setUTCMonth(month [, date])
setFullYear(year [, month [, date]])
setUTCFullYear(year [, month [, date]])
toUTCString()
toISOString()
toJSON()
Additionally, the QML engine adds the following functions to the Date prototype:

timeZoneUpdated()
toLocaleDateString(locale, format)
toLocaleString(locale, format)
toLocaleTimeString(locale, format)
RegExp Objects
RegExp Prototype Object
Function Properties
exec(string)
test(string)
toString()
Error Objects
Error Prototype Object
Value Properties
name
message
Function Properties
toString()
The JSON Object
Function Properties
parse(text [, reviver])
stringify(value [, replacer [, space]])
