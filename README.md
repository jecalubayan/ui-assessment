# UI Assessment Notes

## Build plan
  - The project was built using the Foundation 6 CLI, with the basic template as a starting point
  - From here I started by building the general HTML structure
  - Once the structure was in place, I began styling to match the design, with a mobile first approach
    * Since there was no provided mobile design, I styled mobile up through tablet sizes as I saw fit
    * Certain elements are hidden or rearranged in order to accommodate smaller mobile screens
  - From mobile, I gradually scaled up through sizes and restyled elements as needed, up to desktop where I attmpted to match the provided design
  - I kept all of my styles in a single file 'base.scss' and imported into the main 'app.scss' file
    * Typically I would break up the styles into different imports for media queries or individual modules on larger projects, but I kept them all in one file this time

# Unfinished tasks

## Overall
  - The line-heights, font-sizes, and general spacing between elements needs to be tightened up a bit to match the design
  - The correct matching font should be added, I found a very close match on Typekit, but I don't think it's exact

## Site Header
  - I added a placeholder for the header and intended on revisiting it to add the content from the design
  - For the mobile header I would have:
    * Reduced the logo to the mark, centered
    * Log in on the left, basket icon on the right
    * Removed the photo in the megamenu (only display on larger screens with enough room)
    * Collapsed the rest of the nav into expandable items
  - Make the header sticky

## Buy it by the box
  - The smaller text below the main description needs to be fixed, on desktop it's wrapping

## Drinks
  - The paragraph text is currently too wide on desktop
  - The section header font-size needs to be bigger

## Pick your pleasure
  - The paragraph text is too wide, needs to wrap on desktop
  - Spacing between the drink images is a bit too small

## Cleanse
  - I would have added the background photo similar to how I did in the top hero section

## Locations
  - Spacing between the location images is a bit too small
  - "View store details" text shouldn't wrap on desktop

## Site Footer
  - This is completely missing, I have the beginning of a placeholder but didn't get to add content
  - On mobile, I would have let the content stack
    * If possible, "Company" and "Help" look like they could go side-by-side with "Social" below
  - On mobile, I would have stacked the "email address" field and submit button, made the button full width with the field