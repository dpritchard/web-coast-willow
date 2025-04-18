# Coastal Otago Willows and Weavers 

(Formally *Friends of the Taieri Willow*)

This is the source code and content for a static website built using [Jigsaw][tcj], [Tailwind][twn], [Github Actions][gha] and [Github Pages][ghp]. 

[tcj]: https://jigsaw.tighten.co
[twn]: https://tailwindcss.com
[gha]: https://github.com/features/actions
[ghp]: https://pages.github.com

# Local Builds / Development
In a terminal window in the `web-coast-willow` working directory
```
npm run dev
./vendor/bin/jigsaw serve
bbedit ./
```
Once happy with changes:
```
^c (to cancel the development server...)
git add .
git commmit -m
git push
```

Built for deployment on GitHub using Github actions and a build workflow modified from [here](https://james.brooks.page/blog/jigsaw-github-actions/).
