---
layout: default
title: UI Features
nav_order: 6
---
# UI features


## Selected text formatting options
Below are selected formatting options that may be useful in  in RC worskhop sites.

__Notes__

Use this syntax...

```  
Wash your hands frequently
{: .note}
```
... to include a note that will look like this on the workshop website:

Wash your hands frequently
{: .note}

__Warning__
```
Don't step on the snails!
{: .warn}
```
Don't step on the snails!
{: .warn}

__Danger__
```
Snails armed and dangerous
{: .danger}
```
Snails armed and dangerous
{: .danger}

__Prerequisites.__

This synax...

```
- Basic slug identification
- Comfortable in the woods
{: .prereq}
```
...will look like this:

Something else here  
 - Basic slug identification
 - Comfortable in the woods
{: .prereq}


__Terminal input.__

Use this formatting to indicate that the participant should input text into the terminal or command line. This...

~~~
Input
{: .label .label-green }
```
$ git status
```
~~~
... will appear like this in the workshop website:

Input
{: .label .label-green }
```
$ git status
```

__Terminal output.__

Shows the output resulting from an action.  This syntax...

~~~
Output
{: .label .label-yellow }
```
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
```
~~~

...looks like this on the site:

Output
{: .label .label-yellow }
```
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
```

__Dropdowns__

You can use dropdowns to hide answers to questions. For example:

<details>
<summary>Who was the first U.S. president?</summary>
<br>
George Washington.
</details>

To create hidden content in a dropdown use this:

~~~
<details>
<summary>This is the dropdown title</summary>
<br>
This is the hidden dropdown content.
</details>
~~~

If you want it open by default:
~~~
<details open>
<summary>This is the dropdown title</summary>
<br>
This is the dropdown content that you can hide if you want to.
</details>
~~~
