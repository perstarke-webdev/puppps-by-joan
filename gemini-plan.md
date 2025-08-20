# Plan: Creating Travel & Recipes Page

## 1. Task Description (from gemini-tasks.md)

Joan has provided content for a "Travel and Recipes" section, including two recipes: "Shepherds Pie" and "Basic Homemade Dinner." The goal is to integrate this content into the website. The user is unsure whether to create a new page or a subsection and has asked for my recommendation and a detailed plan.

## 2. Recommendation: New Dedicated Page

Given the distinct nature of the content (recipes) and the potential for future expansion (more recipes, travel content), a **new dedicated page** is the most appropriate solution. This will ensure better site organization, clearer navigation for users, and scalability.

## 3. Execution Plan

Here is the step-by-step plan to create the new "Recipes" page:

1.  **Create New Page File:** I will create a new HTML file at `/Users/perstarke/PSWD/Github Repos/0_Clients/puppps-by-joan/_pages/recipes.html`.

2.  **Define Page Metadata and Layout:** The new file will include standard Jekyll front matter, setting the title to "Recipes" and the permalink to `/recipes`. It will use the `page` layout.

3.  **Structure Content:**
    *   The page will have a main heading: `<h1>Travel & Recipes</h1>`.
        EDIT: Include this in the front matter instead, just like other pages do.
    *   For each recipe, I will create a dedicated section with:
        *   A sub-heading (`<h2>`) for the recipe name (e.g., "Shepherds Pie").
        *   An "Ingredients" section formatted as an unordered list (`<ul>`).
        *   "Instructions" formatted as an ordered list (`<ol>`) or clear paragraphs.
    *   The nutritionist disclaimer for "Basic Homemade Dinner" will be included as a paragraph.

4.  **Integrate Placeholder Images:** I will select appropriate placeholder images from the `assets/images/` directory and include them within the recipe sections. I will use `assets/images/home/book.webp` and `assets/images/home/podcast.webp` as initial placeholders.

5.  **Review and Refine Text:** I will carefully review the provided recipe text for clarity, grammar, and consistency, making minimal necessary adjustments.

6.  **Update Navigation (Optional, but recommended):** After the page is created, I can suggest updating the `_data/navigation.yml` file to include a link to the new "Recipes" page in the site's navigation menu. (This will be a separate step after your approval).
    EDIT: do this immediately as well please.

Please review this plan. Once you confirm, I will proceed with creating the new page.
