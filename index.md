# Show me

Learners clone a repository that contains instructions for an exercise:

```markdown

# Commit a change to a file

1. Add the text "updated" to the bottom of `files/edit-me.txt`
2. Commit that update with the messages "Add updated to edit-me.txt"

# Tag a commit

3. Find the id of the commit that added the text "Nelly" to the `files/animals.txt`
4. Tag that commit with the tag name "elephant"

```

The student tries to complete the exercise

```bash
echo "updates" >> files/edit-me.txt
git add files/edit-me.txt
git commit -m "Change file"
git log files/animals.txt
git tag elephant 26112fa05
```

GitRuler will given instant feedback on whether they have completed each step:

![](images/gr-simple-output-example.png)

Oh, they didn't give the correct message when committing the file. Hopefully they've learned now.

# Student Testimonials

**82%** students prefer GitRuler to other similar undergraduate teaching[^1]
**88%** students learn better from GitRuler than other git tutorials

- _"I find this method of learning git to be fantastic"_
- _"It's a good learning tool. Fairly easy to use once you get the hang of it"_
- _"Gitruler was useful as it showed what needed to be done and gave instant feedback in regards to whether it was completed satisfactorily"_


[^1]: A survey of 17 students using GitRuler as part of an undergraduate course.