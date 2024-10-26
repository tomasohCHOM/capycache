# capycache

Utilizing Data Structures and Algorithms (DSA) to build cool projects!

## What is LRU Cache

A Least Recently Used (LRU) Cache is a caching mechanism where a limited number of items are stored and evicts the least recently accessed item when the cache reaches its maximum capacity. The cache maintains a list of items, where the most recently accessed items are usually placed at the front of the list and the least recently used ones are placed at the end. The data structure is often implemented with a doubly linked list and a hash map to optimize insertion and update operations.

BTW, LRU Cache is a [LeetCode problem](https://leetcode.com/problems/lru-cache/) as well! I recommend solving it to gain a better understanding of how it might be implemented optimally.

## Using LRU Cache

LRU Cache can be applied in a handful of ways and in different places (web browsers, operating systems, and more). In this example, we simulate an emoji keyboard, where we store the 10 most recent emojis used in the cache. Once full capacity is reached, the least recent emojis are no longer considered part of the cache.

See the implementation details of the data structure [here](https://github.com/tomasohCHOM/capycache/blob/main/src/lib/lruCache.js).

## Set up / Development

Clone the repository and install all the dependencies:

```bash
git clone https://github.com/tomasohCHOM/capycache.git
cd capycache
npm install
```

Then start the development process:

```bash
npm run dev
```

---

Developed with 💚 by [Tomas](https://github.com/tomasohCHOM), [Jeremiah](https://github.com/JeremiahHerring), and [acmcsufoss](https://github.com/acmcsufoss)