- 👋 Hi, I’m @rajendra-413
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
rajendra-413/rajendra-413 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
// Creating a hash table using Map
const hashTable = new Map();

// Adding key-value pairs
hashTable.set('name', 'Alice');
hashTable.set('age', 25);
hashTable.set('country', 'USA');

// Accessing values by key
console.log(hashTable.get('name')); // Output: Alice
console.log(hashTable.get('age')); // Output: 25

// Checking if a key exists
console.log(hashTable.has('country')); // Output: true

// Removing a key-value pair
hashTable.delete('age');

// Iterating over key-value pairs
hashTable.forEach((value, key) => {
  console.log(`${key}: ${value}`);
});
// Output:
// name: Alice
// country: USA
