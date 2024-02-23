# Daniel Sebastian Ochoa Urrego

### Git stash list results

stash@{0}: WIP on main: aa1d473 Developers life in a nutshell

### Git merge conflict

```
<<<<<<< HEAD
    watchMovies();
=======
    watchAnime();
>>>>>>> feature-branch
```

### Issues

During this checkpoint I had 2 big issues while doing it:

* I didn't now, but when making the merge we have to change not only the same file but also the same lines in that file for the conflict to appear.
* For the conflict to appear we need to commit our changes on the main branch, if not, git won't even let the merge happen. I think this is because in a typical situation git would be actually saving us from losing the changes we made if we continued with the merge.
* Also, I had to use GitHub, because git didn't work in the company computer so I had to use my PC and couldn't access GitLab :(