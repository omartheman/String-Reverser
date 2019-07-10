//# String-Reverser
// A program in Javascript to reverse the order of the characters in any given string. 

//String Reverse

String.prototype.replaceAt = function (index, replacement) {
    return this.substr(0, index) + replacement + this.substr(index + replacement.length);
}

function stringReverser(pirate) {
 alert(pirate.replaceAt(pirate.length-length, str.charAt(pirate.length -1)))
}

stringReverser("Donkey");
