## Show me

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


