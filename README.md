# Spell-Checker
Trie is a tree-based data structure, which is used for efficient retrieval of a key in a large dataset of strings.

# Trie
Data structure and relevant algorithms for extremely fast prefix/fuzzy string searching.

Trie is an efficient information retrieval data structure. Using Trie, search complexities can be brought to optimal limit (key length). 

If we store keys in a binary search tree, a well balanced BST will need time proportional to **M * log N**, where M is the maximum string length and N is the number of keys in the tree.
<hr>

### [Basic Implementation]
<img src="https://github.com/ethicalADI/Spell-Checker/blob/main/example.png" height="500" />
<hr>

## Demo || Working
 
Open the [folder](https://github.com/ethicalADI/Spell-Checker/blob/main/Output) to view the working and output.

You can get the complete code in one file. [Open This](https://github.com/ethicalADI/Spell-Checker/blob/main/CompleteCode.cpp)

## Usage

Create a Trie with:

```Go
Trie *t = new Trie();
```

Add Keys with:

```Go
// i.e. you could store any information you would like to associate with
// this particular key.
t->insert(name, num);
```

Find a key with:

```Go
bool ok = t->search(s);
```

Remove Keys with:

```Go
t->remove(name);
```

Search with:

```Go
t->search(s);
```

Prefix search with:

```Go
t->starts_with(s);
```

Prefix search with recommendations:
```Go
t->show_recommendations(name);
```


## Contributing
Fork this repo and run tests with:

##

### Connect with me:

[<img align="left" alt="codeSTACKr.com" width="22px" src="https://img.icons8.com/?size=512&id=n9d0Hm43JCPK&format=png" />][website]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" />][linkedin]
[<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" />][instagram]
<br />

[website]: https://ethicaladi.github.io/adityakumar-portfolio/
[instagram]: https://www.instagram.com/adikumar_11
[linkedin]: https://in.linkedin.com/in/aditya-kumar-76b58b225/
