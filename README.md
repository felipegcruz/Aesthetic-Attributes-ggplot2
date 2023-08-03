# Aesthetic Attributes

In this guide, you will learn about the three basic aesthetic attributes to consider when creating ggplot2 visualizations in R: color, size, and shape. These attributes are essential tools for creating data visualizations with ggplot2 and are built directly into its code.

![Image of a triangle, sphere, and cube that are different colors and different sizes. The shapes all have eyes and smiling.](triangle_sphere_cube.png)

## Aesthetics in ggplot2

Ggplot2 is an R package that allows you to create different types of data visualizations right in your R workspace. In ggplot2, an aesthetic is defined as a visual property of an object in your plot.

There are three aesthetic attributes in ggplot2:

1. **Color:** this allows you to change the color of all of the points on your plot, or the color of each data group.

2. **Size:** this allows you to change the size of the points on your plot by data group.

3. **Shape:** this allows you to change the shape of the points on your plot by data group.

Here’s an example of how aesthetic attributes are displayed in R:

```R
ggplot(data, aes(x=distance, y= dep_delay, color=carrier, size=air_time, shape = carrier)) +
  geom_point()
```

By applying these aesthetic attributes to your work with ggplot2, you can create data visualizations in R that clearly communicate trends in your data.

## Additional Resources

For more information about aesthetic attributes, check out these resources:

- [Data visualization with ggplot2 cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf): RStudio’s cheat sheet is a great reference to use while working with ggplot2. It has tons of helpful information, including explanations of how to use geoms and examples of the different visualizations that you can create.

- [Stats Education’s Introduction to R](http://www.stat.columbia.edu/~tzheng/files/Rcolor.pdf): This resource is a great way to learn the basics of ggplot2 and how to apply aesthetic attributes to your plots. You can return to this tutorial as you work more with ggplot2 and your own data.

- [RDocumentation aes function](https://www.rdocumentation.org/packages/ggplot2/versions/3.3.3/topics/aes): This guide describes the syntax of the aes function and explains what each argument does.

---

*Note: This README.md document is derived from the content provided in the reading on aesthetic attributes. The content and examples are originally sourced from that reading.*