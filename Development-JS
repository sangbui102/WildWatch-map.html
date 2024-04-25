
function initMap() {
var myLocation = { lat: 20.890856, lng: -156.478755 };

// Create a map object, and include the MapTypeId to add
// to the map type control.
var map = new google.maps.Map(document.getElementById("map"), {
  center: myLocation,
  zoom: 18,
  mapId: 'bd22e9995c95a05d' // Your Map ID
});

const markers =[
  [
    "Fire",
    20.890856, 
    -156.478755,
    "fire.svg",
    50,
    50 
],

  [
      "SOS",
    20.890880, 
      -156.478755,
      "sos.svg",
      30,
      30 
  ],
  [
      "SOS",
    20.890870, 
      -156.478760,
      "sos.svg",
      30,
      30 
  ],
  [
      "SOS",
    20.890890, 
      -156.478755,
      "sos.svg",
      30,
      30 
  ],
  [
      "SOS",
    20.890895, 
      -156.478764,
      "sos.svg",
      30,
      30 
  ],
  [
      "SOS",
    20.890846, 
      -156.478755,
      "sos.svg",
      30,
      30 
  ],

  [
      "SOS",
    20.890840, 
      -156.478755,
      "sos.svg",
      30,
      30 
  ],
  [
      "SOS",
    20.890833, 
      -156.478752,
      "sos.svg",
      30,
      30 
  ],
  [
      "watch",
    20.889110,
    -156.479761,
      "watch.svg",
      20,
      20 
  ],
  
  [
      "SOS",
    20.888539,
    -156.479735,
      "sos.svg",
      20,
      20 
  ],

  [
      "User",
    20.888614,
    -156.480303,
      "user.svg",
      20,
      20 
  ],

  [
    "User",
  20.889119, 
  -156.474553,
    "user.svg",
    20,
    20 
  ],

  [
    "User",
  20.889096, 
  -156.474667,
    "user.svg",
    20,
    20 
  ],

  [
    "User",
  20.891439, 
  -156.479251,
    "user.svg",
    20,
    20 
  ],
  [
    "User",
  20.891711, 
  -156.479592,
    "user.svg",
    20,
    20 
  ],
  
      [  "User",
  20.891811, 
  -156.480039,
        "user.svg",
        35,
        35 
    ],

  [
    "User",
  20.891569, 
  -156.480940,
    "user.svg",
    35,
    35 
  ],
  [
    "User",
  20.889606, 
  -156.481231,
    "user.svg",
    35,
    35 
  ],

  [
    "User",
  20.890246, 
  -156.481204,
    "user.svg",
    35,
    35 
  ],
  [
    "User",
  20.890146, 
  -156.481571,
    "user.svg",
    35,
    35 
  ],

  [
    "User",
  20.889135, 
  -156.478219,
    "user.svg",
    35,
    35 
  ],

  [
        "User",
  20.889678, 
  -156.479708,
        "user.svg",
        35,
        35 
    ],

  [
    "User",
  20.889399, 
  -156.479563,
    "user.svg",
    35,
    35 
  ],

  [
    "User",
  20.889963, 
  -156.475211,
    "user.svg",
    35,
    35 
  ],

  [
    "User",
  20.888933, 
  -156.473413,
    "user.svg",
    35,
    35 
  ],

  [
    "User",
  20.888824, 
  -156.473688,
    "user.svg",
    35,
    35 
  ],

  [
    "User",
  20.888563, 
  -156.474839,
    "user.svg",
    35,
    35 
  ],

  [
    "User",
  20.889395, 
  -156.474740,
    "user.svg",
    35,
    35 
  ],

  [
    "User",
  20.889096, 
  -156.474667,
    "user.svg",
    35,
    35 
  ],

  
];

for (let i = 0; i < markers.length; i++){
  const currMarker = markers[i];

  const marker = new google.maps.Marker({
    position: { lat: currMarker[1], lng: currMarker[2] },
    map,
    title: currMarker[0],
    icon:{
      url:currMarker[3],
      scaledSize: new google.maps.Size(currMarker[4], currMarker[5])
    },
     animation: google.maps.Animation.DROP
  });
   const inflowindow = new google.maps.InfoWindow({
    content: currMarker[0],
  });
  marker.addListener("click", () => {
    inflowindow.open(map, marker)
  });
}
  
}
// Add a marker to the map at the specified location
