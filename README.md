# REACT-ME-AK_PAGE_DUSHRE_PAGE_JAANA_HO-NAVIAGTE-NAVIGATOR-USENAVIGATE-MOVE_ONE_PAGE_TO_ANOTHER-

##### Need 3 Steps 

```react.js
//STEP:1
import { useNavigate } from "react-router-dom";

//Step:2
 const navigator=useNavigate();

            <button
            // Step:3
            onClick={()=>{
              navigator('/project-description')
            }}
              type="submit"
              className="bg-blue-500 text-white px-6 py-2 rounded-xl hover:bg-blue-600 focus:outline-none focus:ring focus:ring-blue-300"
            >
              Next

  </button>

```
