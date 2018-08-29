# CSS GRID

This project is created to develop the webapp using the CSS grid properties.

### css-grid properties

`grid-template-rows` - To define the number of rows

`grid-template-columns` - To define the number of columns

    possible values : px, fr, repeat.

    eg., eg.2, grid-template-rows: 250px repeat( 2, 100px) 1fr;

#### Naming GRID column
We can name the grid lines using name in `grid-template-rows` or `grid-template-columns` as below.

    eg., grid-template-columns: [col-1-start] 100px [col-1-end col-2-start] 150px [col-2-end col-3-start] 100px [col-3-end];
     

`grid-rows` `grid-columns` - To mention how much element can occupy space.

    eg.1, grid-rows: 2 / -1 - this syntax the element occupy from row 2 to till the end.

    eg.2, grid-column: 2 / span2 - it means the element occupies from row 2 till row 4 (span 2 = 2 rows).
    
    eg.3, grid-columns: col-2-start / col-3-end

`min-content`

`minmax(minvalue, maxvalue)`