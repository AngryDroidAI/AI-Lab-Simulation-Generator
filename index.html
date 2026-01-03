<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Lab Simulation Generator</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027 0%, #203a43 50%, #2c5364 100%);
            color: #e0f7fa;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            padding: 30px 0;
            margin-bottom: 20px;
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #00e5ff, #00b8d4);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 800px;
            margin: 0 auto 20px;
            line-height: 1.6;
        }
        
        .main-app {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin-bottom: 40px;
        }
        
        @media (max-width: 900px) {
            .main-app {
                grid-template-columns: 1fr;
            }
        }
        
        .panel {
            background: rgba(16, 36, 54, 0.85);
            border-radius: 15px;
            padding: 25px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(0, 229, 255, 0.1);
        }
        
        .panel-title {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: #4fc3f7;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .panel-title i {
            font-size: 1.3rem;
        }
        
        textarea {
            width: 100%;
            height: 200px;
            background: rgba(10, 25, 41, 0.9);
            border: 1px solid rgba(79, 195, 247, 0.3);
            border-radius: 10px;
            padding: 15px;
            color: #e0f7fa;
            font-size: 1rem;
            resize: vertical;
            margin-bottom: 15px;
        }
        
        textarea:focus {
            outline: none;
            border-color: #00e5ff;
            box-shadow: 0 0 0 2px rgba(0, 229, 255, 0.2);
        }
        
        .button-group {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        .btn {
            padding: 12px 24px;
            border-radius: 8px;
            border: none;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .btn-primary {
            background: linear-gradient(90deg, #00b8d4, #0091ea);
            color: white;
        }
        
        .btn-primary:hover {
            background: linear-gradient(90deg, #0091ea, #00b8d4);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 145, 234, 0.4);
        }
        
        .btn-secondary {
            background: rgba(79, 195, 247, 0.1);
            color: #4fc3f7;
            border: 1px solid rgba(79, 195, 247, 0.3);
        }
        
        .btn-secondary:hover {
            background: rgba(79, 195, 247, 0.2);
            transform: translateY(-2px);
        }
        
        .example-prompts {
            margin-top: 20px;
            font-size: 0.9rem;
        }
        
        .example-prompts h4 {
            margin-bottom: 10px;
            color: #80deea;
        }
        
        .example-prompts ul {
            list-style-type: none;
            padding-left: 5px;
        }
        
        .example-prompts li {
            padding: 5px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            cursor: pointer;
            transition: all 0.2s;
        }
        
        .example-prompts li:hover {
            color: #4fc3f7;
            padding-left: 5px;
        }
        
        .simulation-container {
            position: relative;
            overflow: hidden;
        }
        
        .simulation-area {
            width: 100%;
            height: 500px;
            background: rgba(10, 25, 41, 0.95);
            border-radius: 10px;
            overflow: hidden;
            position: relative;
            border: 1px solid rgba(0, 229, 255, 0.2);
        }
        
        .ai-lab-title {
            text-align: center;
            padding: 15px;
            background: rgba(0, 0, 0, 0.3);
            border-bottom: 1px solid rgba(0, 229, 255, 0.2);
            color: #80deea;
            font-size: 1.3rem;
        }
        
        .simulation-content {
            padding: 20px;
            height: calc(100% - 60px);
            overflow-y: auto;
        }
        
        .data-node {
            position: absolute;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 0.8rem;
            text-align: center;
            transition: all 0.5s ease;
            cursor: pointer;
            z-index: 10;
        }
        
        .data-node i {
            font-size: 1.5rem;
            margin-bottom: 5px;
        }
        
        .neural-network {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 80%;
            height: 60%;
        }
        
        .layer {
            position: absolute;
            top: 0;
            width: 15%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: space-around;
        }
        
        .neuron {
            width: 30px;
            height: 30px;
            border-radius: 50%;
            background: rgba(0, 229, 255, 0.7);
            margin: 0 auto;
            position: relative;
            box-shadow: 0 0 10px rgba(0, 229, 255, 0.5);
        }
        
        .connection {
            position: absolute;
            background: rgba(0, 229, 255, 0.2);
            height: 2px;
            transform-origin: 0 0;
        }
        
        .output-console {
            background: rgba(0, 0, 0, 0.7);
            border-radius: 8px;
            padding: 15px;
            margin-top: 20px;
            font-family: 'Courier New', monospace;
            font-size: 0.9rem;
            height: 120px;
            overflow-y: auto;
        }
        
        .console-line {
            margin-bottom: 5px;
            padding-bottom: 5px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .loading {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100%;
            color: #4fc3f7;
        }
        
        .spinner {
            width: 50px;
            height: 50px;
            border: 5px solid rgba(79, 195, 247, 0.3);
            border-radius: 50%;
            border-top-color: #00e5ff;
            animation: spin 1s linear infinite;
            margin-bottom: 15px;
        }
        
        @keyframes spin {
            100% { transform: rotate(360deg); }
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(0, 229, 255, 0.7); }
            70% { box-shadow: 0 0 0 10px rgba(0, 229, 255, 0); }
            100% { box-shadow: 0 0 0 0 rgba(0, 229, 255, 0); }
        }
        
        .controls {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }
        
        footer {
            text-align: center;
            padding: 30px 0 20px;
            margin-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        .hidden {
            display: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-robot"></i> AI Lab Simulation Generator</h1>
            <p class="subtitle">Create interactive AI laboratory simulations with your custom prompts. Watch as AI models, neural networks, and data visualizations come to life in your browser.</p>
        </header>
        
        <div class="main-app">
            <div class="panel">
                <h2 class="panel-title"><i class="fas fa-code"></i> Simulation Prompt</h2>
                <p>Describe the AI lab simulation you want to generate. Be as specific as possible for better results.</p>
                
                <textarea id="promptInput" placeholder="Example: Create a simulation of a neural network learning to recognize handwritten digits with three hidden layers and a real-time accuracy visualization.">Create a simulation of a neural network learning to recognize handwritten digits with three hidden layers and a real-time accuracy visualization.</textarea>
                
                <div class="button-group">
                    <button id="generateBtn" class="btn btn-primary">
                        <i class="fas fa-bolt"></i> Generate Simulation
                    </button>
                    <button id="clearBtn" class="btn btn-secondary">
                        <i class="fas fa-eraser"></i> Clear
                    </button>
                    <button id="sampleBtn" class="btn btn-secondary">
                        <i class="fas fa-magic"></i> Load Sample
                    </button>
                </div>
                
                <div class="example-prompts">
                    <h4>Example Prompts:</h4>
                    <ul>
                        <li onclick="loadExample(0)">Visualize a convolutional neural network processing images of cats and dogs</li>
                        <li onclick="loadExample(1)">Show a genetic algorithm evolving robot controllers to navigate a maze</li>
                        <li onclick="loadExample(2)">Create a simulation of a natural language processing model analyzing sentiment in tweets</li>
                        <li onclick="loadExample(3)">Demonstrate a reinforcement learning agent learning to play a simple game</li>
                    </ul>
                </div>
            </div>
            
            <div class="panel simulation-container">
                <h2 class="panel-title"><i class="fas fa-flask"></i> AI Lab Simulation</h2>
                
                <div class="simulation-area">
                    <div class="ai-lab-title" id="simulationTitle">AI Lab Simulation</div>
                    
                    <div class="simulation-content" id="simulationContent">
                        <!-- Simulation will be generated here -->
                        <div class="loading" id="loadingIndicator">
                            <div class="spinner"></div>
                            <p>Awaiting simulation generation...</p>
                            <p>Enter a prompt and click "Generate Simulation"</p>
                        </div>
                        
                        <div id="neuralNetworkSim" class="hidden">
                            <div class="neural-network" id="neuralNetwork"></div>
                            <div id="dataNodes"></div>
                        </div>
                        
                        <div id="genericSim" class="hidden">
                            <div id="genericSimContent"></div>
                        </div>
                    </div>
                </div>
                
                <div class="output-console" id="outputConsole">
                    <div class="console-line">> AI Lab Simulation System initialized.</div>
                    <div class="console-line">> Ready to generate simulation from prompt.</div>
                    <div class="console-line">> Enter a simulation prompt and click generate.</div>
                </div>
                
                <div class="controls">
                    <button id="playBtn" class="btn btn-secondary" disabled>
                        <i class="fas fa-play"></i> Play
                    </button>
                    <button id="pauseBtn" class="btn btn-secondary" disabled>
                        <i class="fas fa-pause"></i> Pause
                    </button>
                    <button id="resetBtn" class="btn btn-secondary" disabled>
                        <i class="fas fa-redo"></i> Reset
                    </button>
                </div>
            </div>
        </div>
        
        <footer>
            <p>AI Lab Simulation Generator | All simulations run locally in your browser | No data is sent to external servers</p>
            <p>Made with <i class="fas fa-heart" style="color:#ff4081;"></i> for AI enthusiasts and educators</p>
        </footer>
    </div>

    <script>
        // Example prompts
        const examplePrompts = [
            "Visualize a convolutional neural network processing images of cats and dogs with accuracy metrics and feature maps",
            "Show a genetic algorithm evolving robot controllers to navigate a maze with mutation and crossover visualization",
            "Create a simulation of a natural language processing model analyzing sentiment in tweets with real-time classification",
            "Demonstrate a reinforcement learning agent learning to play a simple game with Q-values and reward visualization"
        ];
        
        // DOM Elements
        const promptInput = document.getElementById('promptInput');
        const generateBtn = document.getElementById('generateBtn');
        const clearBtn = document.getElementById('clearBtn');
        const sampleBtn = document.getElementById('sampleBtn');
        const simulationTitle = document.getElementById('simulationTitle');
        const simulationContent = document.getElementById('simulationContent');
        const loadingIndicator = document.getElementById('loadingIndicator');
        const neuralNetworkSim = document.getElementById('neuralNetworkSim');
        const genericSim = document.getElementById('genericSim');
        const genericSimContent = document.getElementById('genericSimContent');
        const outputConsole = document.getElementById('outputConsole');
        const playBtn = document.getElementById('playBtn');
        const pauseBtn = document.getElementById('pauseBtn');
        const resetBtn = document.getElementById('resetBtn');
        const neuralNetwork = document.getElementById('neuralNetwork');
        const dataNodes = document.getElementById('dataNodes');
        
        // Simulation state
        let simulationActive = false;
        let simulationInterval = null;
        let simulationStep = 0;
        let simulationType = '';
        
        // Load example prompt
        function loadExample(index) {
            if (index >= 0 && index < examplePrompts.length) {
                promptInput.value = examplePrompts[index];
            }
        }
        
        // Add message to console
        function addConsoleMessage(message) {
            const consoleLine = document.createElement('div');
            consoleLine.className = 'console-line';
            consoleLine.innerHTML = `> ${message}`;
            outputConsole.appendChild(consoleLine);
            outputConsole.scrollTop = outputConsole.scrollHeight;
        }
        
        // Generate simulation based on prompt
        function generateSimulation() {
            const prompt = promptInput.value.trim();
            
            if (!prompt) {
                alert('Please enter a simulation prompt');
                return;
            }
            
            // Show loading
            loadingIndicator.classList.remove('hidden');
            neuralNetworkSim.classList.add('hidden');
            genericSim.classList.add('hidden');
            
            // Disable buttons during generation
            generateBtn.disabled = true;
            generateBtn.innerHTML = '<i class="fas fa-cog fa-spin"></i> Generating...';
            
            // Clear console and add generating message
            outputConsole.innerHTML = '';
            addConsoleMessage(`Parsing prompt: "${prompt.substring(0, 50)}${prompt.length > 50 ? '...' : ''}"`);
            addConsoleMessage("Initializing simulation environment...");
            
            // Determine simulation type based on prompt keywords
            let type = 'generic';
            const promptLower = prompt.toLowerCase();
            
            if (promptLower.includes('neural network') || promptLower.includes('neural') || promptLower.includes('layer')) {
                type = 'neural-network';
            } else if (promptLower.includes('genetic') || promptLower.includes('evolution')) {
                type = 'genetic';
            } else if (promptLower.includes('reinforcement') || promptLower.includes('q-learning')) {
                type = 'reinforcement';
            } else if (promptLower.includes('natural language') || promptLower.includes('nlp') || promptLower.includes('sentiment')) {
                type = 'nlp';
            }
            
            simulationType = type;
            
            // Simulate generation delay
            setTimeout(() => {
                createSimulation(type, prompt);
                
                // Re-enable generate button
                generateBtn.disabled = false;
                generateBtn.innerHTML = '<i class="fas fa-bolt"></i> Generate Simulation';
            }, 1500);
        }
        
        // Create the simulation based on type
        function createSimulation(type, prompt) {
            // Hide loading indicator
            loadingIndicator.classList.add('hidden');
            
            // Set simulation title
            const title = prompt.substring(0, 50) + (prompt.length > 50 ? '...' : '');
            simulationTitle.textContent = title;
            
            // Enable control buttons
            playBtn.disabled = false;
            pauseBtn.disabled = false;
            resetBtn.disabled = false;
            
            // Create specific simulation based on type
            switch(type) {
                case 'neural-network':
                    createNeuralNetworkSimulation(prompt);
                    break;
                case 'genetic':
                    createGeneticAlgorithmSimulation(prompt);
                    break;
                case 'reinforcement':
                    createReinforcementLearningSimulation(prompt);
                    break;
                case 'nlp':
                    createNLPSimulation(prompt);
                    break;
                default:
                    createGenericSimulation(prompt);
            }
            
            // Add console messages
            addConsoleMessage(`Simulation type detected: ${type}`);
            addConsoleMessage("Simulation generated successfully!");
            addConsoleMessage("Click 'Play' to start the simulation");
        }
        
        // Create neural network simulation
        function createNeuralNetworkSimulation(prompt) {
            neuralNetworkSim.classList.remove('hidden');
            genericSim.classList.add('hidden');
            
            // Clear previous simulation
            neuralNetwork.innerHTML = '';
            dataNodes.innerHTML = '';
            
            // Determine layer count from prompt
            let layerCount = 3;
            if (prompt.includes('two') || prompt.includes('2')) layerCount = 2;
            if (prompt.includes('three') || prompt.includes('3')) layerCount = 3;
            if (prompt.includes('four') || prompt.includes('4')) layerCount = 4;
            if (prompt.includes('five') || prompt.includes('5')) layerCount = 5;
            
            // Create neural network layers
            for (let i = 0; i < layerCount; i++) {
                const layer = document.createElement('div');
                layer.className = 'layer';
                layer.style.left = `${15 + i * (70 / (layerCount-1))}%`;
                
                // Each layer has between 3 and 6 neurons
                const neuronCount = Math.floor(Math.random() * 4) + 3;
                
                for (let j = 0; j < neuronCount; j++) {
                    const neuron = document.createElement('div');
                    neuron.className = 'neuron pulse';
                    neuron.style.animationDelay = `${(i+j)*0.2}s`;
                    layer.appendChild(neuron);
                }
                
                neuralNetwork.appendChild(layer);
            }
            
            // Create data nodes
            const nodeTypes = [
                {icon: 'fa-image', color: '#FF4081', label: 'Input Data'},
                {icon: 'fa-chart-line', color: '#7C4DFF', label: 'Metrics'},
                {icon: 'fa-brain', color: '#00E5FF', label: 'Model'},
                {icon: 'fa-database', color: '#76FF03', label: 'Dataset'},
                {icon: 'fa-cogs', color: '#FF9100', label: 'Training'}
            ];
            
            // Position nodes around the neural network
            const positions = [
                {top: '20%', left: '5%'},
                {top: '70%', left: '5%'},
                {top: '10%', left: '85%'},
                {top: '80%', left: '85%'},
                {top: '45%', left: '90%'}
            ];
            
            for (let i = 0; i < 5; i++) {
                const node = document.createElement('div');
                node.className = 'data-node pulse';
                node.style.backgroundColor = nodeTypes[i].color;
                node.style.top = positions[i].top;
                node.style.left = positions[i].left;
                node.innerHTML = `<i class="fas ${nodeTypes[i].icon}"></i>${nodeTypes[i].label}`;
                node.style.boxShadow = `0 0 20px ${nodeTypes[i].color}`;
                dataNodes.appendChild(node);
            }
            
            // Add connections between layers (visual effect)
            setTimeout(() => {
                createNeuralConnections(layerCount);
            }, 500);
            
            // Add console messages
            addConsoleMessage(`Created neural network with ${layerCount} layers`);
            addConsoleMessage("Input data nodes initialized");
            addConsoleMessage("Neural connections established");
        }
        
        // Create visual connections between neural network layers
        function createNeuralConnections(layerCount) {
            // This is a simplified visualization of connections
            addConsoleMessage("Activating neural connections...");
            
            // In a full implementation, we would draw SVG lines between neurons
            // For this demo, we'll just add a console message
            setTimeout(() => {
                addConsoleMessage("Neural network is processing data...");
            }, 800);
        }
        
        // Create genetic algorithm simulation
        function createGeneticAlgorithmSimulation(prompt) {
            neuralNetworkSim.classList.add('hidden');
            genericSim.classList.remove('hidden');
            
            genericSimContent.innerHTML = `
                <h3 style="color: #76FF03; margin-bottom: 15px;">Genetic Algorithm Simulation</h3>
                <div style="display: flex; justify-content: space-between; margin-bottom: 20px;">
                    <div style="background: rgba(118, 255, 3, 0.1); padding: 15px; border-radius: 10px; width: 30%;">
                        <h4 style="color: #76FF03;"><i class="fas fa-dna"></i> Population</h4>
                        <div id="populationDisplay" style="font-size: 2rem; text-align: center;">50</div>
                        <p style="font-size: 0.9rem;">Candidate solutions</p>
                    </div>
                    <div style="background: rgba(255, 64, 129, 0.1); padding: 15px; border-radius: 10px; width: 30%;">
                        <h4 style="color: #FF4081;"><i class="fas fa-chart-line"></i> Fitness</h4>
                        <div id="fitnessDisplay" style="font-size: 2rem; text-align: center;">0.42</div>
                        <p style="font-size: 0.9rem;">Average fitness score</p>
                    </div>
                    <div style="background: rgba(0, 229, 255, 0.1); padding: 15px; border-radius: 10px; width: 30%;">
                        <h4 style="color: #00E5FF;"><i class="fas fa-bolt"></i> Generation</h4>
                        <div id="generationDisplay" style="font-size: 2rem; text-align: center;">1</div>
                        <p style="font-size: 0.9rem;">Current generation</p>
                    </div>
                </div>
                
                <div style="background: rgba(0,0,0,0.3); padding: 15px; border-radius: 10px; margin-bottom: 20px;">
                    <h4 style="color: #FF9100; margin-bottom: 10px;"><i class="fas fa-project-diagram"></i> Evolution Process</h4>
                    <div id="evolutionVisualization" style="height: 150px; display: flex; align-items: flex-end; justify-content: space-around;">
                        <!-- Evolution bars will be generated here -->
                    </div>
                </div>
                
                <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
                    <div>
                        <h4 style="color: #7C4DFF;"><i class="fas fa-cogs"></i> Operations</h4>
                        <ul style="list-style-type: none; margin-top: 10px;">
                            <li style="padding: 8px 0; border-bottom: 1px solid rgba(255,255,255,0.1);">
                                <i class="fas fa-random" style="color: #7C4DFF;"></i> Selection: Tournament
                            </li>
                            <li style="padding: 8px 0; border-bottom: 1px solid rgba(255,255,255,0.1);">
                                <i class="fas fa-exchange-alt" style="color: #7C4DFF;"></i> Crossover: 80% rate
                            </li>
                            <li style="padding: 8px 0;">
                                <i class="fas fa-bolt" style="color: #7C4DFF;"></i> Mutation: 5% rate
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h4 style="color: #00E5FF;"><i class="fas fa-bullseye"></i> Objective</h4>
                        <p style="margin-top: 10px; font-size: 0.95rem;">
                            ${prompt.includes('maze') ? 'Navigate robot through maze' : 
                              prompt.includes('robot') ? 'Optimize robot controller' :
                              'Maximize fitness function'}
                        </p>
                        <div id="bestSolution" style="background: rgba(0, 229, 255, 0.1); padding: 10px; border-radius: 8px; margin-top: 10px; font-family: monospace; font-size: 0.8rem;">
                            0101101010010110
                        </div>
                    </div>
                </div>
            `;
            
            // Initialize evolution visualization bars
            const evolutionViz = document.getElementById('evolutionVisualization');
            for (let i = 0; i < 10; i++) {
                const bar = document.createElement('div');
                bar.style.width = '8%';
                bar.style.height = `${30 + Math.random() * 70}%`;
                bar.style.backgroundColor = i < 3 ? '#76FF03' : '#7C4DFF';
                bar.style.borderRadius = '4px 4px 0 0';
                evolutionViz.appendChild(bar);
            }
            
            addConsoleMessage("Genetic algorithm simulation initialized");
            addConsoleMessage("Population of 50 candidate solutions created");
            addConsoleMessage("Evolution process ready to start");
        }
        
        // Create generic simulation for other types
        function createGenericSimulation(prompt) {
            neuralNetworkSim.classList.add('hidden');
            genericSim.classList.remove('hidden');
            
            const simTypes = [
                {name: "Convolutional Neural Network", icon: "fa-image", color: "#FF4081"},
                {name: "Reinforcement Learning", icon: "fa-gamepad", color: "#7C4DFF"},
                {name: "Natural Language Processing", icon: "fa-language", color: "#00E5FF"},
                {name: "Computer Vision", icon: "fa-eye", color: "#76FF03"},
                {name: "Data Visualization", icon: "fa-chart-bar", color: "#FF9100"}
            ];
            
            // Select a random simulation type or based on prompt
            let simTypeIndex = 0;
            if (prompt.includes('vision') || prompt.includes('image')) simTypeIndex = 3;
            if (prompt.includes('language') || prompt.includes('nlp')) simTypeIndex = 2;
            if (prompt.includes('reinforcement') || prompt.includes('game')) simTypeIndex = 1;
            
            const simType = simTypes[simTypeIndex];
            
            genericSimContent.innerHTML = `
                <h3 style="color: ${simType.color}; margin-bottom: 15px;"><i class="fas ${simType.icon}"></i> ${simType.name} Simulation</h3>
                
                <div style="background: rgba(0,0,0,0.3); padding: 20px; border-radius: 10px; margin-bottom: 20px;">
                    <div style="display: flex; align-items: center; margin-bottom: 15px;">
                        <div style="width: 60px; height: 60px; border-radius: 50%; background: ${simType.color}; display: flex; align-items: center; justify-content: center; margin-right: 15px;">
                            <i class="fas ${simType.icon} fa-2x"></i>
                        </div>
                        <div>
                            <h4 style="color: ${simType.color};">Simulation Details</h4>
                            <p>${prompt.substring(0, 120)}${prompt.length > 120 ? '...' : ''}</p>
                        </div>
                    </div>
                    
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">
                        <div style="background: rgba(255,255,255,0.05); padding: 15px; border-radius: 8px;">
                            <h5><i class="fas fa-tachometer-alt"></i> Performance</h5>
                            <div id="performanceMeter" style="height: 10px; background: rgba(255,255,255,0.1); border-radius: 5px; margin-top: 10px; overflow: hidden;">
                                <div id="performanceFill" style="height: 100%; width: 45%; background: ${simType.color}; border-radius: 5px;"></div>
                            </div>
                            <div style="display: flex; justify-content: space-between; margin-top: 5px;">
                                <span>0%</span>
                                <span id="performanceValue">45%</span>
                                <span>100%</span>
                            </div>
                        </div>
                        
                        <div style="background: rgba(255,255,255,0.05); padding: 15px; border-radius: 8px;">
                            <h5><i class="fas fa-microchip"></i> Processing</h5>
                            <div id="processingActivity" style="height: 30px; display: flex; align-items: center; justify-content: space-around; margin-top: 10px;">
                                ${'<div style="width: 12%; height: 20%; background: ' + simType.color + ';"></div>'.repeat(8)}
                            </div>
                            <p style="text-align: center; margin-top: 5px; font-size: 0.9rem;">Active processing nodes</p>
                        </div>
                    </div>
                </div>
                
                <div style="background: rgba(0,0,0,0.3); padding: 15px; border-radius: 10px;">
                    <h4 style="color: ${simType.color}; margin-bottom: 10px;"><i class="fas fa-stream"></i> Simulation Output</h4>
                    <div id="simOutput" style="font-family: monospace; font-size: 0.9rem; height: 100px; overflow-y: auto; padding: 10px; background: rgba(0,0,0,0.5); border-radius: 5px;">
                        <div>> Initializing ${simType.name.toLowerCase()} simulation...</div>
                        <div>> Loading datasets and models...</div>
                        <div>> Simulation ready. Click 'Play' to start.</div>
                    </div>
                </div>
            `;
            
            addConsoleMessage(`${simType.name} simulation created`);
            addConsoleMessage("Simulation parameters configured from prompt");
            addConsoleMessage("Ready to run simulation");
        }
        
        // Create other simulation types (simplified for this demo)
        function createReinforcementLearningSimulation(prompt) {
            createGenericSimulation(prompt);
            addConsoleMessage("Reinforcement learning simulation configured");
        }
        
        function createNLPSimulation(prompt) {
            createGenericSimulation(prompt);
            addConsoleMessage("Natural language processing simulation configured");
        }
        
        // Start simulation
        function startSimulation() {
            if (simulationActive) return;
            
            simulationActive = true;
            addConsoleMessage("Simulation started");
            
            // Different simulation logic based on type
            if (simulationType === 'neural-network') {
                startNeuralNetworkSimulation();
            } else if (simulationType === 'genetic') {
                startGeneticAlgorithmSimulation();
            } else {
                startGenericSimulation();
            }
        }
        
        // Start neural network simulation
        function startNeuralNetworkSimulation() {
            simulationStep = 0;
            
            simulationInterval = setInterval(() => {
                simulationStep++;
                
                // Animate data nodes
                const nodes = document.querySelectorAll('.data-node');
                nodes.forEach((node, index) => {
                    const offset = simulationStep * 0.5 + index;
                    const pulseSize = 5 + Math.sin(offset) * 3;
                    node.style.boxShadow = `0 0 ${pulseSize * 2}px ${pulseSize}px ${node.style.backgroundColor}`;
                });
                
                // Animate neurons
                const neurons = document.querySelectorAll('.neuron');
                neurons.forEach((neuron, index) => {
                    const offset = simulationStep * 0.3 + index * 0.1;
                    const brightness = 0.5 + 0.5 * Math.sin(offset);
                    neuron.style.backgroundColor = `rgba(0, 229, 255, ${brightness})`;
                });
                
                // Add console updates occasionally
                if (simulationStep % 10 === 0) {
                    const accuracy = 50 + Math.min(50, simulationStep / 2);
                    addConsoleMessage(`Training step ${simulationStep}: Accuracy = ${accuracy.toFixed(1)}%`);
                }
                
                // Stop after 100 steps
                if (simulationStep >= 100) {
                    pauseSimulation();
                    addConsoleMessage("Simulation completed! Final accuracy: 98.2%");
                }
            }, 200);
        }
        
        // Start genetic algorithm simulation
        function startGeneticAlgorithmSimulation() {
            simulationStep = 0;
            
            simulationInterval = setInterval(() => {
                simulationStep++;
                
                // Update displays
                const populationDisplay = document.getElementById('populationDisplay');
                const fitnessDisplay = document.getElementById('fitnessDisplay');
                const generationDisplay = document.getElementById('generationDisplay');
                const bestSolution = document.getElementById('bestSolution');
                
                if (populationDisplay) {
                    generationDisplay.textContent = Math.floor(simulationStep / 5) + 1;
                    
                    const fitness = 0.42 + Math.min(0.58, simulationStep * 0.005);
                    fitnessDisplay.textContent = fitness.toFixed(2);
                    
                    // Update evolution visualization occasionally
                    if (simulationStep % 5 === 0) {
                        const bars = document.querySelectorAll('#evolutionVisualization div');
                        bars.forEach((bar, index) => {
                            const newHeight = 30 + Math.random() * 70;
                            bar.style.height = `${newHeight}%`;
                            bar.style.backgroundColor = index < 3 ? '#76FF03' : '#7C4DFF';
                        });
                        
                        // Update best solution
                        if (bestSolution) {
                            let solution = '';
                            for (let i = 0; i < 16; i++) {
                                solution += Math.random() > 0.1 ? '1' : '0';
                            }
                            bestSolution.textContent = solution;
                        }
                        
                        addConsoleMessage(`Generation ${generationDisplay.textContent}: Best fitness = ${fitness.toFixed(3)}`);
                    }
                }
                
                // Stop after 50 steps
                if (simulationStep >= 50) {
                    pauseSimulation();
                    addConsoleMessage("Evolution completed! Optimal solution found.");
                }
            }, 300);
        }
        
        // Start generic simulation
        function startGenericSimulation() {
            simulationStep = 0;
            
            simulationInterval = setInterval(() => {
                simulationStep++;
                
                // Update performance meter
                const performanceFill = document.getElementById('performanceFill');
                const performanceValue = document.getElementById('performanceValue');
                const simOutput = document.getElementById('simOutput');
                
                if (performanceFill) {
                    const newWidth = 45 + Math.min(55, simulationStep * 0.5);
                    performanceFill.style.width = `${newWidth}%`;
                    performanceValue.textContent = `${Math.round(newWidth)}%`;
                    
                    // Animate processing nodes
                    const processingNodes = document.querySelectorAll('#processingActivity div');
                    processingNodes.forEach((node, index) => {
                        const height = 20 + Math.sin(simulationStep * 0.5 + index) * 50;
                        node.style.height = `${height}%`;
                    });
                    
                    // Add output occasionally
                    if (simulationStep % 8 === 0 && simOutput) {
                        const messages = [
                            "Processing data batch...",
                            "Updating model weights...",
                            "Calculating loss function...",
                            "Validating with test dataset...",
                            "Optimizing hyperparameters..."
                        ];
                        
                        const message = messages[Math.floor(Math.random() * messages.length)];
                        const outputLine = document.createElement('div');
                        outputLine.textContent = `> ${message}`;
                        simOutput.appendChild(outputLine);
                        simOutput.scrollTop = simOutput.scrollHeight;
                    }
                }
                
                // Stop after 60 steps
                if (simulationStep >= 60) {
                    pauseSimulation();
                    addConsoleMessage("Simulation completed successfully!");
                }
            }, 250);
        }
        
        // Pause simulation
        function pauseSimulation() {
            simulationActive = false;
            if (simulationInterval) {
                clearInterval(simulationInterval);
                simulationInterval = null;
            }
            addConsoleMessage("Simulation paused");
        }
        
        // Reset simulation
        function resetSimulation() {
            pauseSimulation();
            simulationStep = 0;
            
            // Reset any simulation-specific elements
            if (simulationType === 'neural-network') {
                // Reset neural network animation
                const neurons = document.querySelectorAll('.neuron');
                neurons.forEach(neuron => {
                    neuron.style.backgroundColor = 'rgba(0, 229, 255, 0.7)';
                });
                
                const nodes = document.querySelectorAll('.data-node');
                nodes.forEach(node => {
                    node.style.boxShadow = `0 0 20px ${node.style.backgroundColor}`;
                });
            }
            
            addConsoleMessage("Simulation reset to initial state");
        }
        
        // Clear prompt
        function clearPrompt() {
            promptInput.value = '';
            promptInput.focus();
        }
        
        // Load sample prompt
        function loadSamplePrompt() {
            const samples = [
                "Create a simulation showing a neural network with 4 layers classifying different types of flowers based on petal and sepal measurements.",
                "Visualize a reinforcement learning agent learning to balance a pole on a moving cart with real-time reward tracking.",
                "Generate a simulation of a convolutional neural network detecting objects in street view images with bounding boxes and confidence scores.",
                "Show a natural language processing model translating sentences between English and French with attention mechanism visualization."
            ];
            
            const randomSample = samples[Math.floor(Math.random() * samples.length)];
            promptInput.value = randomSample;
        }
        
        // Event Listeners
        generateBtn.addEventListener('click', generateSimulation);
        clearBtn.addEventListener('click', clearPrompt);
        sampleBtn.addEventListener('click', loadSamplePrompt);
        playBtn.addEventListener('click', startSimulation);
        pauseBtn.addEventListener('click', pauseSimulation);
        resetBtn.addEventListener('click', resetSimulation);
        
        // Load a sample simulation on initial page load
        window.addEventListener('DOMContentLoaded', () => {
            setTimeout(() => {
                generateSimulation();
            }, 1000);
        });
    </script>
</body>
</html>
