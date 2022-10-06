###### (note that this is only my take of math explanation; take these information with a grain of salt!)

# Expressions and Statements

## Expressions
In algebra, an expression is an evaluable tree-like structure of mathematical objects, such as numbers, variables, fractions, and so on.
Sounds complex? Yeah I get it.

But it's not so complex once you see examples of it:
- $1$
- $6x$
- $3 + 3$
- $\frac{3}{2}$
- $\sqrt{9 + 16}$

Yeah, these are all expressions. Let's look at each of them:
- > $1$
  
  The simplest form of expression. A **constant**, that evaluates to the number $1$.
- > $6x$

  Now we're getting the more complex part. This expression is called a **term**, consisting of a **variable** and a **coefficient**; see that $x$? That's the variable; a varying stuff, meaning we might or might not know the exact value of it, hence we symbolize it using a letter (in this case, the letter $x$). And that $6$ there? It's the coefficient; an expression that is used to multiply the variable (in this case, $x$). So, in that sense, $6x$ is equal to $6 \cdot x$.
  
  Let's examine more examples of variables and coefficients:
  - $\frac{2}{5}y$
  
    Here, we see that the variable is $y$, and the coefficient is $\frac{2}{5}$. Simple enough. \
    Now let's add some twists:
    
    $(x + 2)y$
    
    Bwah, now it might look a bit scary, but let me comfort you a bit. You just need to see it as a tree of expressions. \
    Let's clarify the operations here: \
    $(x + 2) \cdot y$
    
    We can see a little bit of something here. The variable is $y$, and the coefficient is $(x + 2)$. \
    But wait! Isn't $x$ also a variable? Why did I say "the variable is $y$"?
    
    Good question. Well, think of it like this. A term has a variable and a coeffient. In $(x + 2)y$, the *entire term*'s variable is $y$, and its coefficient is $(x + 2)$. \
    Now let's look at the coefficient of that term, which is $(x + 2)$. There are things to unravel:
    - $(...)$ → The braces (also often called parens, or parentheses) is an expression by itself. The brace expression contains, well, another expression, which in this case is;
    - $x + 2$ → This is the sub-expression of the braces said before. There's a catch here. This, by itself, is *1* expression, but it contains *2* expressions. See what I'm talking about? $x + 2$, which is a single expression, contains $x$ (which is a term where the variable is $x$ and the coefficient is $1$) and $2$ (which is a term where it has no variables and a constant value of $2$), operated together with the $+$ sign.
    
    So, the answer to that question? Well, $y$ is the variable because we're talking about the entire term of $(x + 2)y$, whereas $(x + 2)$ is its coefficient.
    
- > $3 + 3$
    
  This is called a **binary operation**; it's an expression that operates on 2 sub-expressions (in this case, $3$ and $3$) with an operator (in this case, $+$). Actually, you might be wondering, what about $1 + 2 - 3$? Or $1 + 2 + 3 + 4$? There can't possibly any specific names of operations for each of these, right?
    
  Yeah, correct. To simplify it, we can call it **$N$-ary operation**, where $N$ is the amount of expressions there are. \
  For example:
  - $1 + 2$ → An $N$-ary operation where $N = 2$, because there are 2 expressions (which are $1$ and $2$), operated with the $+$ sign. Also called a binary operation.
  - $1 + 2 - 3$ → An $N$-ary operation where $N = 3$, because there are 3 expressions (which are $1$, $2$, and $3$), operated in order with $+$ and $-$.
    
- > $\frac{3}{2}$
  
  This is called a **fraction**; a structure with a **numerator** (the expression above) and a **denominator** (the expression below). To put it simply, fractions are basically "a certain part of any size." For example, $\frac{1}{2}$ is one-half or one part out of two. It's actually basically just $\frac{a}{b} = a \div b$; yes, divisions.
  
  Here's a more complex fraction: \
  $\frac{(x + 1)y}{(x - 1)y}$
  
  Here, the numerator is $(x + 1)y$, and the denominator is $(x - 1)y$

###### (I'm not done yet; please don't complain.)
