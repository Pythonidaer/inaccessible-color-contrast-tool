# Inaccessible Color Contrast Tool

This project generates two random colors that do not meet the Web Content Accessibility Guidelines (WCAG) contrast ratios. It displays these colors as foreground and background colors, along with the calculated contrast ratio. The generated color combinations illustrate what inaccessible color contrast ratios look like. Each time you click the "Generate" button, new colors are generated.

And of course, if you prefer an accessible pairing, just click the toggle!

## What is WCAG?

The Web Content Accessibility Guidelines (WCAG) are a set of recommendations for making web content more accessible, primarily for people with disabilities. WCAG is developed through the World Wide Web Consortium (W3C) process, in cooperation with individuals and organizations around the world.

### WCAG Contrast Requirements

The contrast requirements set by WCAG ensure that text is readable for users with visual impairments. The key levels are:

- **Level A:** The minimum contrast ratio for text and images of text.
- **Level AA:** A higher level of contrast ratio requirement for better accessibility.
- **Level AAA:** The highest level of contrast ratio requirement for maximum accessibility.

For the purposes of this tool, we are focusing on generating color pairs that fall below the WCAG Level A requirements, which means:

- **Normal text:** The contrast ratio is less than 3:1.
- **Large text:** The contrast ratio is less than 2.5:1.

You can learn more about WCAG and its guidelines from the following links:

- [Web Content Accessibility Guidelines (WCAG) Overview](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [Understanding WCAG Contrast Requirements](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)

## Purpose of the Project

The primary goal of this project is to help designers and developers understand what inaccessible color combinations look like and to emphasize the importance of following WCAG guidelines. By generating color combinations that do not meet contrast ratio requirements, this tool provides a visual representation of poor accessibility practices.

## Use With Color Contrast Tool

I have also created a color contrast tool that randomly generates 7:1 ratio AAA pairings. Feel free to use one hex code from here for inspiration. You could even combine both projects into one website!

- [Color Contrast Tool](https://color-contrast-tool.vercel.app/)
- [Accessible Color Pairings](https://accessible-color-pairings.vercel.app/)

## Social Media Links

For any questions or feedback, you can reach me on:

- [LinkedIn](https://www.linkedin.com/in/jonamichahammo/)

## License

This project is licensed under the MIT License. This means you are free to use, modify, and distribute the code as long as you include the original license information. See the [LICENSE](LICENSE) file for more details.

## Future Ideas

Here are some potential future enhancements for this project:

- **Clipboard Tool:** Add functionality to copy the generated color codes and contrast ratio to the clipboard for easy use in other projects.
- **Dynamic Setup for Different Text Sizes:** Implement dynamic generation for various text sizes to provide a comprehensive range of color combinations.

Feel free to contribute to the project by cloning and creating new features, making this your own. Together, we can raise awareness about the importance of accessible web design and help create a more inclusive web for everyone.
