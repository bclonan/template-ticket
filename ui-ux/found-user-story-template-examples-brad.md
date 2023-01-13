---
title: Found user story template examples brad
---
Here are some examples of different user story templates for UI/UX design in the software development lifecycle (SDLC), along with a list of variables to fill in and an explanation of how to use each template:

1. **As a \[user], I want \[goal/desire], so that \[benefit]**

   * Example: "As a customer, I want to be able to filter products by color, so that I can easily find the red shirt I'm looking for."
   * Variables to fill in: user (customer), goal/desire (ability to filter products by color), benefit (easily finding a specific product)
   * How to use: This template is a simple and widely used format for writing user stories. It helps to clearly define the user, their goal, and the benefit they will receive by achieving that goal.
   * Pros: Clear, easy to understand, widely used
   * Cons: May not capture all necessary information, or may not be suitable for more complex or technical stories

   ```markdown
    **As a [user], I want [goal/desire], so that [benefit]**
    - As a customer, I want to be able to filter products by color, so that I can easily find the red shirt I'm looking for.
   ```

   ### **User Story Mapping**

   * Example: "As a customer, I want to search for products by category and color, so that I can easily find the red shirt I'm looking for in the 'Clothing' category."
   * Variables to fill in: user (customer), goal/desire (ability to search for products by category and color), benefit (easily finding a specific product in a specific category)
   * How to use: The User Story Mapping framework helps organize user stories into a hierarchical structure based on user goals and priorities. It's important to identify the user's main goal first, and then break down the smaller user stories that will help them achieve that goal.
   * Pros: Clear, easy to understand, well-organized, hierarchical structure
   * Cons: May be difficult to implement, or may not be suitable for more complex or technical stories

   ```markdown
   **User Story Mapping**
   - As a customer, I want to search for products by category and color, so that I can easily find the red shirt I'm looking for in the 'Clothing' category.
   ```

   ## **Double Diamond**

   * Example: "As a customer, I want to be able to filter products by color and size, so that I can easily find the red shirt I'm looking for in my size"
   * Variables to fill in: user (customer), goal/desire (ability to filter products by color and size), benefit (easily finding a specific product in specific size)
   * How to use: The Double Diamond design process divides the design process into four phases: Discover, Define, Develop, and Deliver. It's important to go through each phase to ensure that you have a clear understanding of the problem, a well-defined solution, and a working prototype before final delivery
   * Pros: Clear, well-defined process, easy to understand
   * Cons: May not be suitable for more complex or technical stories

   ```markdown
   **Double Diamond**
   - As a customer, I want to be able to filter products by color and size, so that I can easily find the red shirt I'm looking for in my size
   ```

   **Design Thinking**

   * Example: "As a customer, I want to be able to view product reviews and ratings before making a purchase, so that I can make an informed decision."
   * Variables to fill in: user (customer), goal/desire (ability to view product reviews and ratings), benefit (making an informed decision)
   * How to use: The Design Thinking methodology emphasizes empathy for the user, rapid prototyping, and iterative design. It's important to understand the user's needs and pain points, create multiple prototypes to test and iterate on, and involve the user in the design process.
   * Pros: Emphasis on user empathy and testing, iterative design process
   * Cons: May not be suitable for more complex or technical stories, may require more time and resources

   ```markdown
   **Design Thinking**
   - As a customer, I want to be able to view product reviews and ratings before making a purchase, so that I can make an informed decision.
   ```

## Additional

**Given \[context], when \[action], then \[outcome]**

* Example: "Given that I am on the product page, when I select the 'Add to Cart' button, then the item should be added to my shopping cart."
* Variables to fill in: context (on the product page), action (selecting the 'Add to Cart' button), outcome (item should be added to shopping cart)
* How to use: This template helps to clearly define the context, action, and expected outcome of a user story, making it easier for QA to test later on in the SDLC.
* Pros: Clear, easy to understand, helps with QA
* Cons: May not capture all necessary information, or may not be suitable for more complex or technical stories

```markdown
**Given [context], when [action], then [outcome]**
- Given that I am on the product page, when I select the 'Add to Cart' button, then the item should be added to my shopping cart.
```

**\[User] can \[action] \[object] \[outcome]**

* Example: "Customer can filter products by color and size and easily find the red shirt they are looking for in their size."
* Variables to fill in: user (customer), action (filter), object (products), outcome (easily find the red shirt they are looking for in their size)
* How to use: This template helps to clearly define the user, action, object, and outcome of a user story, making it easy for QA to understand the expected functionality and test it later on in the SDLC.
* Pros: Clear, easy to understand, helps with QA
* Cons: May not capture all necessary information, or may not be suitable for more complex or technical stories

```markdown
**[User] can [action] [object] [outcome]**
- Customer can filter products by color and size and easily find the red shirt they are looking for in their size.
```

**\[User] should be able to \[action] \[object] \[outcome]**

* Example: "Customer should be able to sort products by price and see the cheapest items first"
* Variables to fill in: user (customer), action (sort), object (products), outcome (see the cheapest items first)
* How to use: This template is similar to the previous one, but it is more directed to the user's needs and goals, and it makes it clear the expected functionality to be tested later on in the SDLC.
* Pros: Clear, easy to understand, helps with QA
* Cons: May not capture all necessary information, or may not be suitable for more complex or technical stories

```markdown
**[User] can [action] [object] [outcome]**
- Customer can filter products by color and size and easily find the red shirt they are looking for in their size.
```

# Some react-native theoretical examples

**Given that a user has earned a reward, when they navigate to the rewards screen, then they should see their available rewards**

* Variables to fill in: context (user has earned a reward), action (navigating to the rewards screen), outcome (user sees their available rewards)
* How to use: This template helps to clearly define the context, action, and expected outcome of a user story, making it easy for QA to test later on in the SDLC. The xstate will help to manage the state of the rewards earned by the user and how they can be consumed.
* Pros: Clear, easy to understand, helps with QA
* Cons: May not capture all necessary information, or may not be suitable for more complex or technical stories

```markdown
**Given that a user has earned a reward, when they navigate to the rewards screen, then they should see their available rewards**
- Given that a user has earned a reward, when they navigate to the rewards screen, then they should see their available rewards.
```

**User should be able to redeem rewards on the rewards screen**

* Variables to fill in: user (customer), action (redeem), object (rewards), outcome (redeem rewards)
* How to use: This template helps to clearly define the user, action, object, and outcome of a user story, making it easy for QA to understand the expected functionality and test it later on in the SDLC. The xstate will help to manage the state of the rewards and how they can be consumed.
* Pros: Clear, easy to understand, helps with QA
* Cons: May not capture all necessary information, or may not be suitable for more complex or technical stories

```markdown
**User should be able to redeem rewards on the rewards screen**
- User should be able to redeem rewards on the rewards screen.
```

**Given that a user has reached a certain level, when they navigate to the rewards screen, then they should see the level-up reward**

* Variables to fill in: context (user has reached a certain level), action (navigating to the rewards screen), outcome (user sees the level-up reward)
* How to use: This template helps to clearly define the context, action, and expected outcome of a user story, making it easy for QA to test later on in the SDLC. The xstate will help to manage the state of the rewards and how they can be consumed.
* Pros: Clear, easy to understand, helps with QA
* Cons: May not capture all necessary information, or may not be suitable for more complex or technical stories

**Given that a user has reached a certain level, when they navigate to the rewards screen, then they should see the level-up reward**



* Variables to fill in: context (user has submitted an invalid entry on first login), action (submitting the form), outcome (user sees a toast notification with an error message and is denied access)
* How to use: This template helps to clearly define the context, action, and expected outcome of a user story, making it easy for QA to test later on in the SDLC. The xstate will help to manage the state of the login process and how to handle invalid entries.
* Pros: Clear, easy to understand, helps with QA
* Cons: May not capture all necessary information, or may not be suitable for more complex or technical stories

```markdown
**Given that a user has reached a certain level, when they navigate to the rewards screen, then they should see the level-up reward**
- Given that a user has reached a certain level, when they navigate to the rewards screen, then they should see the level-up reward.

```