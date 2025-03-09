# 3D Swimming Duck Water Shader 🐣

A beautiful 3D scene featuring a swimming duck in a pool with an advanced water shader effect, built with React Three Fiber and GLSL. The project showcases realistic water animation with foam effects that are more dense around the edges of the pool and the duck.



## Features 🚀

- Custom water shader with animated foam effects
- Dynamic foam density around objects
- Configurable water properties (color, opacity, foam density, etc.)
- Real-time adjustable parameters through Leva controls
- Depth-based rendering for realistic object interactions
- Multiple noise function options (Perlin, Voronoi)

## Technologies Used 💻

- React Three Fiber
- Three.js
- GLSL Shaders
- Lygia Shader Library
- resolve-lygia

## Credits 📝

This project was created following the excellent tutorial from [Wawa Sensei's 3D Web Development Course](https://wawasensei.dev/). The course provides in-depth knowledge about Three.js and React Three Fiber through practical, hands-on projects.

### Assets Used 📦
- Swimming pool model by Poly by Google (CC-BY via Poly Pizza)
- Duck model from Pmndrs marketplace

## Getting Started 🚀

1. Clone the repository:
```bash
git clone https://github.com/pakagronglb/3d-swimming-duck-water-shader.git
```

2. Install dependencies:
```bash
yarn install
```

3. Run the development server:
```bash
yarn dev
```

## Controls ⚙️

The water shader can be customized using the following parameters:

- Water Color
- Water Opacity
- Animation Speed
- Noise Pattern Scale
- Foam Density
- Foam Top Threshold
- Noise Type (Perlin/Voronoi)
- Maximum Depth for Foam Effect

## Implementation Details 📦

The project implements several advanced graphics programming concepts:

- Custom shader materials using React Three Fiber's `shaderMaterial`
- Render targets for depth-based effects
- Integration of the Lygia Shader Library for noise functions
- Dynamic uniform updates for real-time parameter adjustments
- Depth texture rendering for object interaction

## License 🙏🏻

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments 📝

Special thanks to:
- [Wawa Sensei](https://wawasensei.dev/) for the excellent tutorial and course materials
- The React Three Fiber community
- The creators of the Lygia Shader Library

## Learn More 📝 

To learn more about 3D web development and create similar projects, check out:
- [Wawa Sensei's Courses](https://wawasensei.dev/)
- [React Three Fiber Documentation](https://docs.pmnd.rs/react-three-fiber)
- [Three.js Documentation](https://threejs.org/docs/)
