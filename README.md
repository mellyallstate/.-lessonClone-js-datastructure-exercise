# .-lessonClone-js-datastructure-exercise
const solarSystem = [
	{ name: "Mercury", ringSystem: false, moons: [] },
	{ name: "Venus", ringSystem: false, moons: [] },
	{ name: "Earth", ringSystem: false, moons: ["The Moon"] },
	{ name: "Mars", ringSystem: false, moons: ["Phobos", "Deimos"] },
	{ name: "Jupiter", ringSystem: true, moons: ["Europa", "Ganymede", "Io", "Callisto"] },
	{ name: "Saturn", ringSystem: true, moons: ["Titan", "Enceladus", "Rhea", "Mimas"] },
	{ name: "Uranus", ringSystem: true, moons: ["Miranda", "Titania", "Ariel", "Umbriel"] },
	{ name: "Neptune", ringSystem: true, moons: ["Triton", "Nereid"] }
];

console.log(solarSystem[4].moons)

console.log(solarSystem[7].moons[1])

solarSystem[1].moons = "Endor";

solarSystem.push({name: "Pluto", ringSystem: false, moons: ["Charon"]});
solarSystem[2].diameter = "7917.5";

solarSystem[0].ringSystem = true;

solarSystem[6].moons[4] = "Oberon";

for (let i = 0; i < solarSystem.length; i++) {
   if (solarSystem[i].ringSystem) {
       console.log(solarSystem[i]);
   }
}
