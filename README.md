# Calendar Graph

## Requirements

1. Display specific days ago date block.
2. Display difference state color.
3. Auto scale when need difference width and height block
4. Auto flow when start date isn't Jan.
5. Cross multiple years can scale width and auto flow.
6. Show legends.
7. Show Tooltip (now use MUI tooltip).
8. Simple version for specific env.


import Palette from "./Graph/Palette";
import "./Playground.css";

function Playground() {
  return (
    <div className="playground-container">
      <div className="playground-title">
        <h1>Calendar Graph</h1>
      </div>
      <div className="playground-palette">
        <Palette />
      </div>

      <div className="playground-block">1</div>
      <div className="playground-block">2</div>
      <div className="playground-block">3</div>
    </div>
  );
}

export default Playground;
