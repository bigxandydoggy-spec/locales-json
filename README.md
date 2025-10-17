/* 📄 assets/css/sensitivity-tester.css */
.sensitivity-tester-container {
    display: grid;
    grid-template-columns: 300px 1fr;
    gap: 2rem;
    margin-top: 2rem;
}

.sensitivity-controls {
    background: var(--color-gray);
    padding: 1.5rem;
    border-radius: 10px;
    border-left: 4px solid var(--color-primary);
}

.sensitivity-sliders {
    margin: 1.5rem 0;
}

.slider-group {
    display: flex;
    align-items: center;
    margin-bottom: 1rem;
    gap: 1rem;
}

.slider-group label {
    min-width: 120px;
    color: #ccc;
}

.slider-group input[type="range"] {
    flex: 1;
}

.slider-group span {
    min-width: 30px;
    text-align: center;
    font-weight: bold;
    color: var(--color-gold);
}

.sensitivity-presets {
    margin-top: 2rem;
}

.preset-buttons {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 0.5rem;
    margin-top: 0.5rem;
}

.sensitivity-test-area {
    background: var(--color-gray);
    padding: 1.5rem;
    border-radius: 10px;
    border-left: 4px solid var(--color-primary);
}

.sensitivity-canvas-container {
    position: relative;
    margin-top: 1rem;
}

#sensitivityCanvas {
    width: 100%;
    height: 400px;
    background: #1a1a1a;
    border-radius: 8px;
    border: 2px solid #444;
    cursor: crosshair;
}

.sensitivity-stats {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin-top: 1rem;
    text-align: center;
}

.stat {
    background: rgba(255, 255, 255, 0.05);
    padding: 1rem;
    border-radius: 8px;
    border: 1px solid rgba(255, 255, 255, 0.1);
}

.stat span:first-child {
    color: #ccc;
    display: block;
    margin-bottom: 0.5rem;
}

.stat span:last-child {
    font-size: 1.5rem;
    font-weight: bold;
    color: var(--color-gold);
} 
 