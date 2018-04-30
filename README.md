# react-flexi-image-grid
React js Flexible Image Grid View

<h2>How to install ?</h2> 
<pre>
yarn add react-flexi-image-grid
</pre>


<br />
<br />

<h2>Examples:</h2>

 <h2>4 Columns:</h2>
 
![4 columns pics](./example-pics/ss1.png)

 <h2>2 Columns:</h2>
 
![2 columns pics](./example-pics/ss3.png)


<h1>How to use it ? </h1>

```
import React, {Component} from "react";
import {FlexiImageGrid} from "react-flexi-image-grid";


class App extends Component {

    onClickHandler = (e) => {
        console.log(e.target.id);
        console.log(e.target.className);
        console.log(e.target.src);

    };

    render() {
        return (
            <div className="App">

                <FlexiImageGrid
                    images={[

                        {

                            src: "https://www.w3schools.com/w3images/wedding.jpg",
                            className: "img1",
                            id: "idImg1",
                            height: "",
                            alt: "here 1",

                        },

                        {
                            src: "https://www.w3schools.com/w3images/wedding.jpg",
                            className: "img2",
                            height: "150px",

                        },

                        {
                            src: "https://www.w3schools.com/w3images/wedding.jpg",
                            className: "img3"
                        },

                        {
                            src: "https://www.w3schools.com/w3images/rocks.jpg",
                            className: "img4"
                        },

                        {
                            src: "https://www.w3schools.com/w3images/rocks.jpg",
                            className: "img5"
                        }
                        ,
                        {
                            src: "https://www.w3schools.com/w3images/rocks.jpg",
                            className: "img6"
                        },
                        {
                            src: "https://www.w3schools.com/w3images/mountainskies.jpg",
                            className: "img7"
                        },
                        {
                            src: "https://www.w3schools.com/w3images/nature.jpg",
                            className: "img8"
                        },
                        {
                            src: "https://www.w3schools.com/w3images/nature.jpg",
                            className: "img9"

                        },
                        {
                            src: "https://www.w3schools.com/w3images/nature.jpg",
                            className: "img10"
                        },
                        {
                            src: "https://www.w3schools.com/w3images/mist.jpg",
                            className: "img11"
                        },

                        {
                            src: "https://www.w3schools.com/w3images/nature.jpg",
                            className: "img12"
                        },
                        {
                            src: "https://www.w3schools.com/w3images/nature.jpg",
                            className: "img13"
                        },
                        {
                            src: "https://www.w3schools.com/w3images/nature.jpg",
                            className: "img14"
                        },
                        {
                            src: "https://www.w3schools.com/w3images/nature.jpg",
                            className: "img15"
                        },

                    ]}

                    numberOfColumns={4}
                    onClick={this.onClickHandler}

                />

            </div>
        );
    }
}

export default App;

```





