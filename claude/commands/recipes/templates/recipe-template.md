<!-- 
Instructions: Replace all [placeholders] or <place-holders> with actual values
Remove sections marked as optional if they don't apply
-->

---
<!-- Fill this in with the default value of 1 every time.-->
sidebar_position: [SIDEBAR_POSITION]
---

import Admonition from '@theme/Admonition'
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# [RECIPE_NAME]

<Tabs>
  <TabItem value="photos" label="Photos" default>
    <!-- Fill this in with a 2-3 sentence description of the recipe. -->
    [DESCRIPTION]

    ![image](@site/docs/static/img/not-found.svg)
  </TabItem>

  <TabItem value="ingredients" label="Ingredients"
    <!-- Fill this in with an ingredients list for the recipe. If the recipe is multi step, include multiple of these sections.
    Use the following format for each section of ingredients:
    ## Ingredients
    ```text title="Ingredients"
    1 cup all-purpose flour
    1 cup vegetable oil (plus 1 tablespoon)
    3 ribs celery, diced small
    ```
    -->
    [INGREDIENTS]
    
    <!-- If there is a specific tip for the ingredients mentioned in the webpage, add an Info Admonition similar to the following example, preserving the proper indentations:
    <Admonition type="info" title="About the Roux">
      <p>
       Roux is normally done when you smell a peanut butter-like aroma;
      </p>
    </Admonition>
    -->
    [INFO_ADMONITION]
    
    <!-- If there is a specific warning for the ingredients mentioned in the webpage, add a Warning Admonition similar to the following example, preserving the proper indentations:
    <Admonition type="warning" title="Don't Forget To Stir">
      <p>
        A dark roux adds deep flavor but can burn easily. Stir constantly over low heat.
      </p>
    </Admonition>
    -->
    [WARNING_ADMONITION]

  </TabItem>

  <TabItem value="instructions" label="Instructions">

<!-- 
Fill in the instructions for the recipe. Steps should be numbered, and whenever an ingredient from any ingredient list is mentioned, surround it with double asterisks to bold it in the markdown syntax (e.g. **celery**).
    Use the following as an example, preserving the proper indentations:

    1. In a large dutch oven, heat **vegetable oil** over low heat. Add **flour** and stir essentially constantly until the roux becomes dark brown. This can take between 30-60 mins depending on the stove. 
    2. Place the dutch oven with the finished roux over medium heat and add **celery**, **onion**, and **bell pepper**. Cook for 8 to 10 minutes, stirring frequently, until the vegetables have softened and the **onions** are translucent.
    3. Add the **garlic** and **creole seasoning** and cook for about 1 minute or until the **garlic** is fragrant.
-->
    [INSTRUCTIONS]

<!-- If there is a specific tip for the instructions mentioned in the webpage, add an Info Admonition similar to the following example, preserving the proper indentations:
    <Admonition type="info" title="About the Roux">
      <p>
       Roux is normally done when you smell a peanut butter-like aroma;
      </p>
    </Admonition>
-->
    [INFO_ADMONITION]
    
<!-- If there is a specific warning for the instructions mentioned in the webpage, add a Warning Admonition similar to the following example, preserving the proper indentations:
    <Admonition type="warning" title="Don't Forget To Stir">
      <p>
        A dark roux adds deep flavor but can burn easily. Stir constantly over low heat.
      </p>
    </Admonition>
-->
    [WARNING_ADMONITION]
  </TabItem>

  <TabItem value="references" label="References">
    <!-- Create a link to the original source that the user linked. Use this example:
    [Original Recipe](https://southernbite.com/chicken-sausage-and-shrimp-gumbo/)
    -->
    [REFERENCES]
  </TabItem>
</Tabs>

