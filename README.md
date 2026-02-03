# Variables, Properties, and Data Types (Blocks)

## Introduction
In this tutorial, you will learn how **variables** are used to control **sprite properties** in MakeCode Arcade.  
You will also learn the difference between **number variables** and **text (string) variables**, and why using the correct type matters.

👉 When you see **Canvas Prompt**, stop and answer the question in your **Canvas assignment** before continuing.

---

## Step 1: Look at the Program (Blocks View)

Make sure your editor is in **Blocks view**.

You should see:
- Several variables (`num1`, `numStr`, `num4`, etc.)
- A sprite called **buffet**
- Blocks that set the sprite's **position** and **velocity**

Take a moment to look at how the blocks are connected.

---

## Step 2: Sprite Properties

Sprites have **properties**.  
Properties describe things about a sprite, such as:
- Where it is on the screen
- How fast it moves

Find the block that sets the buffet sprite's position.

📝 **Canvas Prompt:**  
In your Canvas assignment, answer this question:

**What is an example of a sprite property shown in the blocks?**

---

## Step 3: Property Values

Properties need **values**.

In the position block, the values come from **variables**, not numbers typed directly into the block.

📝 **Canvas Prompt:**  
In your Canvas assignment, answer this question:

**What values are being used for the property you identified?**

---

## Step 4: Variables Store Values

Variables store information that the program can use later.

Using variables allows programmers to:
- Change values easily
- Reuse values in different blocks
- Keep code organized

Look at the variables list and notice that some variables store numbers, and one stores text.

---

## Step 5: Number Variables

Some variables store **numbers**.

Examples in this program include:
- `num1`
- `num4`

Number variables are used for:
- Position
- Speed
- Movement

📘 **Syntax Rule:**  
Number variables **do not** have quotation marks.

---

## Step 6: Text (String) Variables

Look at the variable named `numStr`.

Even though it looks like it contains a number, it is actually **text**.

Text variables:
- Have quotation marks
- Are treated like words, not numbers
- Cannot be used for movement or math

📝 **Canvas Prompt:**  
In your Canvas assignment, answer this question:

**Why is `numStr` a different type of variable than `num1`?**

---

## Step 7: Create an Error (Blocks)

Find the block that sets the buffet sprite's position.

Replace the **number variable** in the position block with the **text variable** `numStr`.

▶ Run the game.

📝 **Canvas Prompt:**  
In your Canvas assignment, answer this question:

**What happens when you use `numStr` in the position block and run the program?**

---

## Step 8: Read the Error Message

When the program does not work, look for the **triangle with an exclamation point**.

Click it to see the error message.

📝 **Canvas Prompt:**  
In your Canvas assignment, answer this question:

**What error message does MakeCode show?**

---

## Step 9: Why the Error Happens

The position block requires **number values**.

Because `numStr` is **text**, MakeCode cannot use it to place the sprite on the screen.

This causes a **type error**.

---

## Wrap-Up 🎯

- Sprites have **properties**
- Properties use **values**
- Values can come from **variables**
- **Number variables** control movement
- **Text variables** are for words
- Using the wrong variable type causes an error

Before leaving this tutorial, make sure all **Canvas Prompts** are answered.



> Open this page at [https://pompommom.github.io/part-2-variable-manipulation-integers/](https://pompommom.github.io/part-2-variable-manipulation-integers/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/pompommom/part-2-variable-manipulation-integers** and import

## Edit this project

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/pompommom/part-2-variable-manipulation-integers** and click import

#### Metadata (used for search, rendering)

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
