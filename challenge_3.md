## The goal of this challenge is to calculate the number of solutions to the following equation and display the number of solutions.

## `ax²+bx+c=0`

You are given 3 integers on the same line separated by a space:

- You will receive:
  - `a`,`b`,`c` -> A string containing three integers

  
To solve this challenge, you should compute `d` with the following formula :

## `d=b²-4ac`

.
Once done, you can get the solution based on the value of d

Now based on the value of `d`, you can determine the number of solutions :

- `d < 0` -> no solution.
- `d == 0` -> one solution.
- `d > 0` -> two solutions.
 
⚠️ ** Constraint ** ⚠️

`a`,`b` and `c` are integers.
 
## Here are a few example to help you :

<div
    style="
        display: flex;
        flex-direction: row;
        width: 100%;"
>
<div
    style="
        display: flex;
        flex-direction: column;
        width: 50%;"
>
<p
    style="
        width: 100%;
        font-weight: bold;"
> Inputs</p>

```bash
1 0 -4
```

</div>
</br>
<div
    style="
        display: flex;
        flex-direction: column;
        padding-left: 5%;
        width: 50%;"
>
<p
    style="
        width: 100%;
        font-weight: bold;"
> Outputs</p>

```bash
2
```

</div>
</div>
</br>
<div
    style="
        display: flex;
        flex-direction: row;
        width: 100%;"
>
<div
    style="
        display: flex;
        flex-direction: column;
        width: 50%;"
>
<p
    style="
        width: 100%;
        font-weight: bold;"
> Inputs</p>

```bash
1 2 1
```

</div>
</br>
<div
    style="
        display: flex;
        flex-direction: column;
        padding-left: 5%;
        width: 50%;"
>
<p
    style="
        width: 100%;
        font-weight: bold;"
> Outputs</p>

```bash
1
```

</div>
</div>
