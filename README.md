# pcct
Product Comparison Chart Template

1. copy style

    `cp ./pcc/stylesheets/asciidoc-style-ing.css /usr/local/Cellar/asciidoc/9.1.0/etc/asciidoc/.`

2. generate slidedeck

    `asciidoc --backend slidy -o product-comparison-chart-slidedeck.html product-comparison-chart.adoc`
   
3. Configuration

    - Font-Based Icons
    
        https://asciidoctor.org/docs/asciidoctor-pdf/#font-based-icons

        https://blog.mrhaki.com/2014/06/awesome-asciidoc-use-inline-icons.html

4. PDF customization

   - font 
   
      https://www.wimdeblauwe.com/blog/2019/2019-12-20-customization-of-asciidoctor-pdf-output/

      https://github.com/asciidoctor/asciidoctor-pdf/blob/v1.5.0.beta.5/docs/theming-guide.adoc#custom-fonts

      https://github.com/asciidoctor/asciidoctor-pdf/blob/v1.5.0.beta.5/docs/theming-guide.adoc#preparing-a-custom-font