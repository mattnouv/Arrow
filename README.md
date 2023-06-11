<b>Arrow Functions Exercise</b>
<br><br>In this exercise, you’ll refactor some ES5 code into ES2015.

<i>ES5 Map Callback<br></i>
function double(arr) {<br>
  return arr.map(function(val) {<br>
    return val * 2;<br>
  });<br>
}
<p><i>ES2015 Arrow Functions Shorthand<br></i></p>
Refactor the above code to use two arrow functions. Turn it into a one-liner.

<i>/* Write an ES2015 Version */<br></i>
<b>Refactor the following function to use arrow functions:
Replace ALL functions with arrow functions:</b>

function squareAndFindEvens(numbers){<br>
  var squares = numbers.map(function(num){<br>
    return num ** 2;<br>
  });<br>
  var evens = squares.filter(function(square){<br>
    return square % 2 === 0;<br>
  });<br>
  return evens;<br>
}
