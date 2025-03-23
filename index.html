<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="theme-color" content="#2980b9">
    <title>Workout Tracker</title>
    <style>
        * {
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
        }
        body {
            font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f8f9fa;
            -webkit-text-size-adjust: 100%;
        }
        .app-container {
            max-width: 100%;
            margin: 0 auto;
            padding: 10px;
        }
        header {
            background-color: #2980b9;
            color: white;
            padding: 15px;
            text-align: center;
            margin-bottom: 15px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        header h1 {
            margin: 0;
            font-size: 1.4rem;
        }
        .workout-tabs {
            display: flex;
            background-color: #fff;
            border-radius: 8px;
            overflow: hidden;
            margin-bottom: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .tab {
            flex: 1;
            padding: 12px 4px;
            text-align: center;
            cursor: pointer;
            transition: all 0.2s ease;
            font-weight: bold;
            font-size: 0.7rem;
        }
        .tab.active {
            background-color: #2980b9;
            color: white;
        }
        .workout-container {
            display: none;
            padding: 12px;
            background-color: #fff;
            border-radius: 8px;
            margin-bottom: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .workout-container.active {
            display: block;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
            border-radius: 8px;
            overflow: hidden;
            font-size: 0.85rem;
        }
        th, td {
            border: 1px solid #e0e0e0;
            padding: 8px 4px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
            font-weight: 600;
            font-size: 0.8rem;
        }
        input[type="number"] {
            width: 45px;
            padding: 6px 4px;
            border: 1px solid #ddd;
            border-radius: 4px;
            background-color: #f9f9f9;
            font-size: 0.85rem;
        }
        .date-container {
            margin-bottom: 15px;
        }
        input[type="date"] {
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
            background-color: #f9f9f9;
        }
        button {
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 4px;
            font-weight: 600;
            transition: background-color 0.3s;
            margin: 5px 0;
            font-size: 0.9rem;
        }
        .save-btn {
            background-color: #27ae60;
            color: white;
            width: 100%;
        }
        .history-session {
            margin-bottom: 20px;
            padding: 15px;
            background-color: #f8f9fa;
            border-left: 5px solid #3498db;
            border-radius: 4px;
        }
        .notes-area {
            width: 100%;
            height: 60px;
            margin-bottom: 15px;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-family: inherit;
        }
        .history-toggle {
            background-color: #3498db;
            color: white;
            margin-bottom: 10px;
            width: 100%;
        }
        .history-container {
            display: none;
            margin-top: 20px;
        }
        .history-container.active {
            display: block;
        }
        .exercise-name {
            font-weight: bold;
            font-size: 0.85rem;
        }
        .export-btn {
            background-color: #9b59b6;
            color: white;
            width: 100%;
            margin-top: 10px;
        }
        .button-group {
            display: flex;
            margin-bottom: 15px;
            flex-direction: column;
        }
        .notification {
            padding: 12px;
            margin: 10px 0;
            border-radius: 4px;
            display: none;
            text-align: center;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        .prev-value {
            font-size: 0.8rem;
            color: #666;
            display: block;
            background-color: #f5f5f5;
            padding: 4px;
            border-radius: 3px;
            text-align: center;
            min-height: 1.2em;
        }
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.8rem;
            color: #7f8c8d;
            padding: 10px;
        }
    </style>
</head>
<body>
    <div class="app-container">
        <header>
            <h1>Workout Tracker</h1>
        </header>
        
        <div id="notification" class="notification"></div>
        
        <div class="workout-tabs">
            <div class="tab active" onclick="changeTab(0)">Monday:<br>Back & Biceps</div>
            <div class="tab" onclick="changeTab(1)">Wednesday:<br>Chest & Shoulders</div>
            <div class="tab" onclick="changeTab(2)">Friday:<br>Legs & Abs</div>
        </div>
        
        <div class="workout-container active" id="day1">
            <div class="date-container">
                <label for="day1-date">Date: </label>
                <input type="date" id="day1-date">
            </div>
            
            <table>
                <thead>
                    <tr>
                        <th>Exercise</th>
                        <th>Last Weight</th>
                        <th>Weight</th>
                        <th>Last Reps</th>
                        <th>Reps</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="exercise-name">Deadlift</td>
                        <td><span class="prev-value" id="prev-weight-1-Deadlift">-</span></td>
                        <td><input type="number" class="weight-input" data-day="1" data-exercise="Deadlift"></td>
                        <td><span class="prev-value" id="prev-reps-1-Deadlift">-</span></td>
                        <td><input type="number" class="reps-input" data-day="1" data-exercise="Deadlift"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Barbell Row</td>
                        <td><span class="prev-value" id="prev-weight-1-Barbell Row">-</span></td>
                        <td><input type="number" class="weight-input" data-day="1" data-exercise="Barbell Row"></td>
                        <td><span class="prev-value" id="prev-reps-1-Barbell Row">-</span></td>
                        <td><input type="number" class="reps-input" data-day="1" data-exercise="Barbell Row"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Pull Up</td>
                        <td><span class="prev-value" id="prev-weight-1-Pull Up">-</span></td>
                        <td><input type="number" class="weight-input" data-day="1" data-exercise="Pull Up"></td>
                        <td><span class="prev-value" id="prev-reps-1-Pull Up">-</span></td>
                        <td><input type="number" class="reps-input" data-day="1" data-exercise="Pull Up"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Dumbbell Curl</td>
                        <td><span class="prev-value" id="prev-weight-1-Dumbbell Curl">-</span></td>
                        <td><input type="number" class="weight-input" data-day="1" data-exercise="Dumbbell Curl"></td>
                        <td><span class="prev-value" id="prev-reps-1-Dumbbell Curl">-</span></td>
                        <td><input type="number" class="reps-input" data-day="1" data-exercise="Dumbbell Curl"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Preacher Curl</td>
                        <td><span class="prev-value" id="prev-weight-1-Preacher Curl">-</span></td>
                        <td><input type="number" class="weight-input" data-day="1" data-exercise="Preacher Curl"></td>
                        <td><span class="prev-value" id="prev-reps-1-Preacher Curl">-</span></td>
                        <td><input type="number" class="reps-input" data-day="1" data-exercise="Preacher Curl"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Shrug</td>
                        <td><span class="prev-value" id="prev-weight-1-Shrug">-</span></td>
                        <td><input type="number" class="weight-input" data-day="1" data-exercise="Shrug"></td>
                        <td><span class="prev-value" id="prev-reps-1-Shrug">-</span></td>
                        <td><input type="number" class="reps-input" data-day="1" data-exercise="Shrug"></td>
                    </tr>
                </tbody>
            </table>
            
            <div>
                <label for="day1-notes">Notes:</label>
                <textarea id="day1-notes" class="notes-area" placeholder="How did the workout feel?"></textarea>
            </div>
            
            <div class="button-group">
                <button class="save-btn" onclick="saveWorkout(1)">Save Workout</button>
                <button class="history-toggle" onclick="toggleHistory(1)">Show/Hide History</button>
            </div>
            
            <div class="history-container" id="history-1">
                <!-- History will be populated here -->
            </div>
        </div>
        
        <div class="workout-container" id="day2">
            <div class="date-container">
                <label for="day2-date">Date: </label>
                <input type="date" id="day2-date">
            </div>
            
            <table>
                <thead>
                    <tr>
                        <th>Exercise</th>
                        <th>Last Weight</th>
                        <th>Weight</th>
                        <th>Last Reps</th>
                        <th>Reps</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="exercise-name">Bench Press</td>
                        <td><span class="prev-value" id="prev-weight-2-Bench Press">-</span></td>
                        <td><input type="number" class="weight-input" data-day="2" data-exercise="Bench Press"></td>
                        <td><span class="prev-value" id="prev-reps-2-Bench Press">-</span></td>
                        <td><input type="number" class="reps-input" data-day="2" data-exercise="Bench Press"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Incline Press</td>
                        <td><span class="prev-value" id="prev-weight-2-Incline Press">-</span></td>
                        <td><input type="number" class="weight-input" data-day="2" data-exercise="Incline Press"></td>
                        <td><span class="prev-value" id="prev-reps-2-Incline Press">-</span></td>
                        <td><input type="number" class="reps-input" data-day="2" data-exercise="Incline Press"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Shoulder Press</td>
                        <td><span class="prev-value" id="prev-weight-2-Shoulder Press">-</span></td>
                        <td><input type="number" class="weight-input" data-day="2" data-exercise="Shoulder Press"></td>
                        <td><span class="prev-value" id="prev-reps-2-Shoulder Press">-</span></td>
                        <td><input type="number" class="reps-input" data-day="2" data-exercise="Shoulder Press"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Lateral Raise</td>
                        <td><span class="prev-value" id="prev-weight-2-Lateral Raise">-</span></td>
                        <td><input type="number" class="weight-input" data-day="2" data-exercise="Lateral Raise"></td>
                        <td><span class="prev-value" id="prev-reps-2-Lateral Raise">-</span></td>
                        <td><input type="number" class="reps-input" data-day="2" data-exercise="Lateral Raise"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Reverse Fly</td>
                        <td><span class="prev-value" id="prev-weight-2-Reverse Fly">-</span></td>
                        <td><input type="number" class="weight-input" data-day="2" data-exercise="Reverse Fly"></td>
                        <td><span class="prev-value" id="prev-reps-2-Reverse Fly">-</span></td>
                        <td><input type="number" class="reps-input" data-day="2" data-exercise="Reverse Fly"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Tricep Extension</td>
                        <td><span class="prev-value" id="prev-weight-2-Tricep Extension">-</span></td>
                        <td><input type="number" class="weight-input" data-day="2" data-exercise="Tricep Extension"></td>
                        <td><span class="prev-value" id="prev-reps-2-Tricep Extension">-</span></td>
                        <td><input type="number" class="reps-input" data-day="2" data-exercise="Tricep Extension"></td>
                    </tr>
                </tbody>
            </table>
            
            <div>
                <label for="day2-notes">Notes:</label>
                <textarea id="day2-notes" class="notes-area" placeholder="How did the workout feel?"></textarea>
            </div>
            
            <div class="button-group">
                <button class="save-btn" onclick="saveWorkout(2)">Save Workout</button>
                <button class="history-toggle" onclick="toggleHistory(2)">Show/Hide History</button>
            </div>
            
            <div class="history-container" id="history-2">
                <!-- History will be populated here -->
            </div>
        </div>
        
        <div class="workout-container" id="day3">
            <div class="date-container">
                <label for="day3-date">Date: </label>
                <input type="date" id="day3-date">
            </div>
            
            <table>
                <thead>
                    <tr>
                        <th>Exercise</th>
                        <th>Last Weight</th>
                        <th>Weight</th>
                        <th>Last Reps</th>
                        <th>Reps</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="exercise-name">Squat</td>
                        <td><span class="prev-value" id="prev-weight-3-Squat">-</span></td>
                        <td><input type="number" class="weight-input" data-day="3" data-exercise="Squat"></td>
                        <td><span class="prev-value" id="prev-reps-3-Squat">-</span></td>
                        <td><input type="number" class="reps-input" data-day="3" data-exercise="Squat"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Leg Press</td>
                        <td><span class="prev-value" id="prev-weight-3-Leg Press">-</span></td>
                        <td><input type="number" class="weight-input" data-day="3" data-exercise="Leg Press"></td>
                        <td><span class="prev-value" id="prev-reps-3-Leg Press">-</span></td>
                        <td><input type="number" class="reps-input" data-day="3" data-exercise="Leg Press"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Leg Extension</td>
                        <td><span class="prev-value" id="prev-weight-3-Leg Extension">-</span></td>
                        <td><input type="number" class="weight-input" data-day="3" data-exercise="Leg Extension"></td>
                        <td><span class="prev-value" id="prev-reps-3-Leg Extension">-</span></td>
                        <td><input type="number" class="reps-input" data-day="3" data-exercise="Leg Extension"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Deadlift</td>
                        <td><span class="prev-value" id="prev-weight-3-Deadlift">-</span></td>
                        <td><input type="number" class="weight-input" data-day="3" data-exercise="Deadlift"></td>
                        <td><span class="prev-value" id="prev-reps-3-Deadlift">-</span></td>
                        <td><input type="number" class="reps-input" data-day="3" data-exercise="Deadlift"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Leg Curl</td>
                        <td><span class="prev-value" id="prev-weight-3-Leg Curl">-</span></td>
                        <td><input type="number" class="weight-input" data-day="3" data-exercise="Leg Curl"></td>
                        <td><span class="prev-value" id="prev-reps-3-Leg Curl">-</span></td>
                        <td><input type="number" class="reps-input" data-day="3" data-exercise="Leg Curl"></td>
                    </tr>
                    <tr>
                        <td class="exercise-name">Calf Raise</td>
                        <td><span class="prev-value" id="prev-weight-3-Calf Raise">-</span></td>
                        <td><input type="number" class="weight-input" data-day="3" data-exercise="Calf Raise"></td>
                        <td><span class="prev-value" id="prev-reps-3-Calf Raise">-</span></td>
                        <td><input type="number" class="reps-input" data-day="3" data-exercise="Calf Raise"></td>
                    </tr>
                </tbody>
            </table>
            
            <div>
                <label for="day3-notes">Notes:</label>
                <textarea id="day3-notes" class="notes-area" placeholder="How did the workout feel?"></textarea>
            </div>
            
            <div class="button-group">
                <button class="save-btn" onclick="saveWorkout(3)">Save Workout</button>
                <button class="history-toggle" onclick="toggleHistory(3)">Show/Hide History</button>
            </div>
            
            <div class="history-container" id="history-3">
                <!-- History will be populated here -->
            </div>
        </div>
        
        <div style="margin-top: 20px; text-align: center;">
            <button class="export-btn" onclick="exportAllWorkouts()">Export All Workouts</button>
        </div>
        
        <footer>
            Workout Tracker - v1.0
        </footer>
    </div>
    
    <script>
        // Initialize workout history in localStorage if it doesn't exist
        if (!localStorage.getItem('workoutHistory')) {
            localStorage.setItem('workoutHistory', JSON.stringify({
                day1: [],
                day2: [],
                day3: []
            }));
        }
        
        // Set today's date as default for date inputs
        document.addEventListener('DOMContentLoaded', function() {
            const today = new Date().toISOString().split('T')[0];
            document.getElementById('day1-date').value = today;
            document.getElementById('day2-date').value = today;
            document.getElementById('day3-date').value = today;
            
            // Load workout history
            loadWorkoutHistory(1);
            loadWorkoutHistory(2);
            loadWorkoutHistory(3);
            
            // Load previous workout data for each exercise
            loadPreviousWorkoutData(1);
            loadPreviousWorkoutData(2);
            loadPreviousWorkoutData(3);
        });
        
        // Load previous workout data for the specified day
        function loadPreviousWorkoutData(day) {
            const history = JSON.parse(localStorage.getItem('workoutHistory'));
            const dayHistory = history[`day${day}`];
            
            if (dayHistory.length === 0) {
                return; // No history available
            }
            
            // Get the most recent workout
            const lastWorkout = dayHistory[0];
            
            // Update the "Last" columns for each exercise
            lastWorkout.exercises.forEach(exercise => {
                const weightElement = document.getElementById(`prev-weight-${day}-${exercise.name}`);
                const repsElement = document.getElementById(`prev-reps-${day}-${exercise.name}`);
                
                if (weightElement) {
                    weightElement.textContent = exercise.weight || '-';
                }
                
                if (repsElement) {
                    repsElement.textContent = exercise.reps || '-';
                }
            });
        }
        
        // Show notification
        function showNotification(message, type) {
            const notification = document.getElementById('notification');
            notification.textContent = message;
            notification.className = 'notification ' + type;
            notification.style.display = 'block';
            
            // Hide after 3 seconds
            setTimeout(() => {
                notification.style.display = 'none';
            }, 3000);
        }
        
        // Change workout tab
        function changeTab(tabIndex) {
            const tabs = document.querySelectorAll('.tab');
            const containers = document.querySelectorAll('.workout-container');
            
            tabs.forEach((tab, index) => {
                if (index === tabIndex) {
                    tab.classList.add('active');
                    containers[index].classList.add('active');
                } else {
                    tab.classList.remove('active');
                    containers[index].classList.remove('active');
                }
            });
        }
        
        // Save workout
        function saveWorkout(day) {
            const date = document.getElementById(`day${day}-date`).value;
            const notes = document.getElementById(`day${day}-notes`).value;
            
            // Get current values
            const exercises = [];
            const dayContainerId = `day${day}`;
            const dayContainer = document.getElementById(dayContainerId);
            
            const weightInputs = dayContainer.querySelectorAll('.weight-input');
            const repsInputs = dayContainer.querySelectorAll('.reps-input');
            
            for (let i = 0; i < weightInputs.length; i++) {
                const exerciseName = weightInputs[i].getAttribute('data-exercise');
                const weight = weightInputs[i].value || 0;
                const reps = repsInputs[i].value || 0;
                
                exercises.push({
                    name: exerciseName,
                    weight: weight,
                    reps: reps
                });
            }
            
            const workout = {
                date: date,
                notes: notes,
                exercises: exercises,
                timestamp: new Date().getTime()
            };
            
            try {
                // Save to local storage
                const history = JSON.parse(localStorage.getItem('workoutHistory'));
                history[`day${day}`].unshift(workout); // Add to beginning of array
                localStorage.setItem('workoutHistory', JSON.stringify(history));
                
                // Reload history
                loadWorkoutHistory(day);
                
                // Update the "Last" values
                loadPreviousWorkoutData(day);
                
                // Clear form fields
                clearFormFields(day);
                
                showNotification('Workout saved successfully!', 'success');
            } catch (error) {
                console.error('Error saving workout:', error);
                showNotification('Error saving workout. Please try again.', 'error');
            }
        }
        
        // Clear form fields after saving
        function clearFormFields(day) {
            const dayContainerId = `day${day}`;
            const dayContainer = document.getElementById(dayContainerId);
            
            const weightInputs = dayContainer.querySelectorAll('.weight-input');
            const repsInputs = dayContainer.querySelectorAll('.reps-input');
            
            weightInputs.forEach(input => input.value = '');
            repsInputs.forEach(input => input.value = '');
            
            document.getElementById(`day${day}-notes`).value = '';
        }
        
        // Load workout history
        function loadWorkoutHistory(day) {
            const history = JSON.parse(localStorage.getItem('workoutHistory'));
            const dayHistory = history[`day${day}`];
            const historyContainer = document.getElementById(`history-${day}`);
            
            historyContainer.innerHTML = '';
            
            if (dayHistory.length === 0) {
                historyContainer.innerHTML = '<p>No workout history available.</p>';
                return;
            }
            
            dayHistory.forEach((workout, index) => {
                const sessionDiv = document.createElement('div');
                sessionDiv.className = 'history-session';
                
                let sessionHtml = `<h3>Session on ${workout.date}</h3>`;
                
                if (workout.notes) {
                    sessionHtml += `<p><strong>Notes:</strong> ${workout.notes}</p>`;
                }
                
                sessionHtml += '<table class="history-table"><thead><tr><th>Exercise</th><th>Weight</th><th>Reps</th></tr></thead><tbody>';
                
                workout.exercises.forEach(exercise => {
                    sessionHtml += `
                        <tr>
                            <td>${exercise.name}</td>
                            <td>${exercise.weight}</td>
                            <td>${exercise.reps}</td>
                        </tr>
                    `;
                });
                
                sessionHtml += '</tbody></table>';
                
                // Add buttons for this workout
                sessionHtml += `
                    <div class="button-group">
                        <button onclick="deleteWorkout(${day}, ${index})">Delete</button>
                        <button onclick="loadWorkoutToForm(${day}, ${index})">Load to Form</button>
                    </div>
                `;
                
                sessionDiv.innerHTML = sessionHtml;
                historyContainer.appendChild(sessionDiv);
            });
        }
        
        // Load a previous workout to the form
        function loadWorkoutToForm(day, index) {
            const history = JSON.parse(localStorage.getItem('workoutHistory'));
            const workout = history[`day${day}`][index];
            
            const dayContainerId = `day${day}`;
            const dayContainer = document.getElementById(dayContainerId);
            
            // Set date
            document.getElementById(`day${day}-date`).value = workout.date;
            
            // Set notes
            document.getElementById(`day${day}-notes`).value = workout.notes;
            
            // Set exercises
            workout.exercises.forEach(exercise => {
                const weightInput = dayContainer.querySelector(`.weight-input[data-exercise="${exercise.name}"]`);
                const repsInput = dayContainer.querySelector(`.reps-input[data-exercise="${exercise.name}"]`);
                
                if (weightInput) weightInput.value = exercise.weight;
                if (repsInput) repsInput.value = exercise.reps;
            });
            
            showNotification('Workout loaded to form', 'success');
        }
        
        // Delete workout
        function deleteWorkout(day, index) {
            if (confirm('Are you sure you want to delete this workout?')) {
                try {
                    const history = JSON.parse(localStorage.getItem('workoutHistory'));
                    history[`day${day}`].splice(index, 1);
                    localStorage.setItem('workoutHistory', JSON.stringify(history));
                    loadWorkoutHistory(day);
                    
                    // Update the "Last" values since we may have deleted the most recent workout
                    loadPreviousWorkoutData(day);
                    
                    showNotification('Workout deleted successfully', 'success');
                } catch (error) {
                    console.error('Error deleting workout:', error);
                    showNotification('Error deleting workout', 'error');
                }
            }
        }
        
        // Toggle history visibility
        function toggleHistory(day) {
            const historyContainer = document.getElementById(`history-${day}`);
            historyContainer.classList.toggle('active');
        }
        
        // Export all workout data
        function exportAllWorkouts() {
            const history = JSON.parse(localStorage.getItem('workoutHistory'));
            
            if (history.day1.length === 0 && history.day2.length === 0 && history.day3.length === 0) {
                showNotification('No workout data to export!', 'error');
                return;
            }
            
            let csvContent = 'data:text/csv;charset=utf-8,';
            
            // Add headers
            csvContent += 'Date,Workout Day,Exercise,Weight,Reps,Notes\n';
            
            // Add data for all days
            ['day1', 'day2', 'day3'].forEach((dayKey, dayIndex) => {
                const dayName = dayIndex === 0 ? 'Monday' : dayIndex === 1 ? 'Wednesday' : 'Friday';
                
                history[dayKey].forEach(workout => {
                    workout.exercises.forEach(exercise => {
                        const safeNotes = workout.notes ? workout.notes.replace(/"/g, '""') : '';
                        csvContent += `${workout.date},"${dayName}","${exercise.name}",${exercise.weight},${exercise.reps},"${safeNotes}"\n`;
                    });
                });
            });
            
            try {
                // Create download link
                const encodedUri = encodeURI(csvContent);
                const link = document.createElement('a');
                link.setAttribute('href', encodedUri);
                link.setAttribute('download', 'workout_data.csv');
                document.body.appendChild(link);
                link.click();
                document.body.removeChild(link);
                
                showNotification('Export successful', 'success');
            } catch (error) {
                console.error('Error exporting data:', error);
                showNotification('Error exporting data', 'error');
            }
        }
    </script>
</body>
</html>
