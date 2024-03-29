---
layout: page
title: Styles
nav_order: 5
permalink: Styles/Styles
---
# Styles

You can use various styles to create a consistent look across your documents. Styles are building blocks to transform boring text into visually appealing and functional structures. In addition to Product A default styles, you can also create your own custom styles using CSS.

{: .note-title }
>**Note**
>
>You can import a custom .css file rather than creating one from scratch. For more information, see [Import a CSS File](#import-a-css-file).
>

## Before you start

There are a few prerequisites you'll need to complete before you can create your own custom styles.

### You'll need to verify you have the following:

* Your company's branding guidelines, such as:
  * Typography, such as fonts and spacing
  * Color palettes
  * Logos, such as light/dark logos, horizontal/vertical, etc., for flexible placement.
* Your company's brand assets, such as:
  * Icons
  * Photos
  * Illustrations
* Basic understanding of HTML and CSS syntax.

{: .note-title }
>**Note**
>
>Not sure what HTML/CSS means? Learn more [here](https://www.w3schools.com/html/html_css.asp).
> 

## Use Product A Default Styles

Product A has default styles you can use in your documents; you can easily modify the font, background, margins, and borders of default styles to suit your needs.

1. Open your document.
2. In your document, place your cursor in the text to which you want to apply the style.
3. Click **Styles**.
4. Select the style to apply to the text.

    For example, if you want to apply an h1 style, select **h1**.
    
    By default, Product A's h1 style uses Times New Roman, size 32 bolded font, black color, and no background. You can change this; see [Create Custom Styles Using CSS](#create-custom-styles-using-css).

## Create Custom Styles Using CSS

You can directly create/edit styles using Product A's built-in CSS Editor.

1. Open your document.
2. Click **Styles**.
3. Right-click the style you want to modify.
4. Click **Edit With CSS Editor**.
5. Using Product A's CSS Editor, you can easily change the selected style's:
   * **Font** - Font-family, font-size, font-weight, color, and more.
   * **Background** - background-color, background-image, and more.
   * **Margins** - margin, margin-left, margin-right, margin-top, and margin-bottom.
   * **Border** - border-width, border-style, border-color.
   * **Text Decoration** - underlines, strikethroughs, and more.
6. Click **Advanced** to display and change advanced properties, such as:
   * **Animations and Transitions** - Add dynamic animation and transition properties.
   * **Box-shadow** - Add depth and dimension using box-shadow.
   * **Transformations** - Rotate, scale, or skew elements using transform and translate properties.
7. Click **Save** to apply your changes to the style.

## Add a CSS File

If you already have a .CSS file with defined styles, you can add it into the **Stylesheets** folder. .CSS files saved in the **Stylesheets** folder can be associated with documents.

1. Open Windows Explorer and navigate to the **Product A** folder.
2. Open the **Assets** folder.
3. Open the **Stylesheets** folder.
4. Save a copy of the .CSS file into the **Stylesheets** folder.
  
   The .CSS file is now available in Product A.
5. You can then [associate a document with a css file](#associate-a-document-with-a-css-file).

## Import a CSS File

If you already have a .CSS file with defined styles, you can import it into Product A.

1. Click **File > Import > CSS**.
2. Select the .CSS file.
3. Click **Import**.
    The .CSS file is imported into Product A. Imported .CSS files can be found in the **Stylesheets** folder within Product A (Product A\Assets\Stylesheets).
4. You can then [associate a document with a .CSS File](#associate-a-document-with-a-css-file).

## Associate a Document  with a .CSS File
You must associate a document with a .CSS file in order to leverage the styles from that .CSS file. Otherwise, documents are associated with Product A's default styles (Default.CSS).

1. Click **File > Advanced**.
2. Click **CSS**.
3. In **Associated CSS**, select the .CSS file to associate with the document.
4. Click **Apply Changes**.
5. Verify the appropriate styles are now available.