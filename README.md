# Banker's Algorithm Simulator

A React-based web application that demonstrates the Banker's Algorithm for deadlock avoidance in operating systems. This interactive tool helps visualize how the algorithm works to prevent deadlocks in resource allocation.

## Features

- Interactive interface for inputting processes and resources
- Real-time visualization of the Banker's Algorithm
- Step-by-step execution of the algorithm
- Detection of safe and unsafe states
- Responsive design that works on different screen sizes

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher) or Yarn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bankers-algorithm.git
   cd bankers-algorithm
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:5173
   ```

## How to Use

1. Enter the number of processes and resources
2. Input the available resources
3. Fill in the allocation and need matrices
4. Click "Run Algorithm" to see the results
5. Follow the step-by-step execution to understand how the algorithm works

## Building for Production

To create a production build:

```bash
npm run build
```

This will create a `dist` folder with the optimized production build.

## Technologies Used

- React 18
- Vite
- JavaScript (ES6+)
- CSS3

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
