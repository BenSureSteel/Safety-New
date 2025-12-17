<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Management Basics</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 12px;
            box-shadow: 0 10px 40px rgba(0,0,0,0.2);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .header h1 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        .header p {
            opacity: 0.9;
        }

        .content {
            padding: 30px;
        }

        .lesson-section {
            margin-bottom: 30px;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 8px;
            border-left: 4px solid #667eea;
        }

        .lesson-section h2 {
            color: #333;
            margin-bottom: 15px;
            font-size: 1.5em;
        }

        .lesson-section p {
            color: #555;
            line-height: 1.6;
            margin-bottom: 10px;
        }

        .quiz-container {
            margin-top: 30px;
            padding: 25px;
            background: #fff3cd;
            border-radius: 8px;
            border: 2px solid #ffc107;
        }

        .quiz-container h3 {
            color: #333;
            margin-bottom: 20px;
        }

        .question {
            margin-bottom: 20px;
        }

        .question p {
            font-weight: bold;
            margin-bottom: 10px;
            color: #333;
        }

        .options {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .option {
            padding: 12px;
            background: white;
            border: 2px solid #ddd;
            border-radius: 6px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .option:hover {
            border-color: #667eea;
            background: #f0f4ff;
        }

        .option.selected {
            border-color: #667eea;
            background: #e8eeff;
        }

        .option.correct {
            border-color: #28a745;
            background: #d4edda;
        }

        .option.incorrect {
            border-color: #dc3545;
            background: #f8d7da;
        }

        .submit-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 12px 30px;
            border-radius: 6px;
            font-size: 1em;
            cursor: pointer;
            margin-top: 20px;
            transition: background 0.3s;
        }

        .submit-btn:hover {
            background: #5568d3;
        }

        .submit-btn:disabled {
            background: #ccc;
            cursor: not-allowed;
        }

        .result {
            margin-top: 20px;
            padding: 15px;
            border-radius: 6px;
            font-weight: bold;
            text-align: center;
        }

        .result.success {
            background: #d4edda;
            color: #155724;
            border: 2px solid #28a745;
        }

        .result.partial {
            background: #fff3cd;
            color: #856404;
            border: 2px solid #ffc107;
        }

        .progress-bar {
            width: 100%;
            height: 8px;
            background: #e0e0e0;
            border-radius: 4px;
            overflow: hidden;
            margin-top: 10px;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #667eea 0%, #764ba2 100%);
            transition: width 0.5s;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>📚 Project Management Basics</h1>
            <p>Learn the fundamentals of effective project management</p>
            <div class="progress-bar">
                <div class="progress-fill" id="progressBar" style="width: 0%"></div>
            </div>
        </div>

        <div class="content">
            <div class="lesson-section">
                <h2>🎯 What is Project Management?</h2>
                <p>Project management is the application of knowledge, skills, tools, and techniques to project activities to meet project requirements. It involves planning, organizing, and managing resources to bring about the successful completion of specific project goals and objectives.</p>
            </div>

            <div class="lesson-section">
                <h2>📊 The Five Phases</h2>
                <p><strong>1. Initiation:</strong> Define the project at a high level and get authorization to start.</p>
                <p><strong>2. Planning:</strong> Establish the scope, objectives, and procedures necessary to complete the project.</p>
                <p><strong>3. Execution:</strong> Complete the work defined in the project plan to satisfy project requirements.</p>
                <p><strong>4. Monitoring & Controlling:</strong> Track, review, and regulate progress and performance.</p>
                <p><strong>5. Closing:</strong> Finalize all activities and formally close the project.</p>
            </div>

            <div class="lesson-section">
                <h2>🔑 Key Success Factors</h2>
                <p>Successful projects typically have clear goals, strong leadership, effective communication, proper resource allocation, and stakeholder engagement throughout the project lifecycle.</p>
            </div>

            <div class="quiz-container">
                <h3>✅ Knowledge Check</h3>
                
                <div class="question">
                    <p>1. Which phase involves defining the project at a high level?</p>
                    <div class="options">
                        <label class="option">
                            <input type="radio" name="q1" value="a"> Planning
                        </label>
                        <label class="option">
                            <input type="radio" name="q1" value="b"> Initiation
                        </label>
                        <label class="option">
                            <input type="radio" name="q1" value="c"> Execution
                        </label>
                    </div>
                </div>

                <div class="question">
                    <p>2. What is the main focus during the Monitoring & Controlling phase?</p>
                    <div class="options">
                        <label class="option">
                            <input type="radio" name="q2" value="a"> Starting new tasks
                        </label>
                        <label class="option">
                            <input type="radio" name="q2" value="b"> Tracking progress and performance
                        </label>
                        <label class="option">
                            <input type="radio" name="q2" value="c"> Closing the project
                        </label>
                    </div>
                </div>

                <div class="question">
                    <p>3. Which is NOT mentioned as a key success factor?</p>
                    <div class="options">
                        <label class="option">
                            <input type="radio" name="q3" value="a"> Clear goals
                        </label>
                        <label class="option">
                            <input type="radio" name="q3" value="b"> Unlimited budget
                        </label>
                        <label class="option">
                            <input type="radio" name="q3" value="c"> Effective communication
                        </label>
                    </div>
                </div>

                <button class="submit-btn" onclick="checkAnswers()">Submit Answers</button>
                <div id="result"></div>
            </div>
        </div>
    </div>

    <script>
        const answers = {q1: 'b', q2: 'b', q3: 'b'};
        let progressValue = 0;

        document.querySelectorAll('.option').forEach(option => {
            option.addEventListener('click', function() {
                const radio = this.querySelector('input[type="radio"]');
                radio.checked = true;
                
                const name = radio.name;
                document.querySelectorAll(`input[name="${name}"]`).forEach(r => {
                    r.parentElement.classList.remove('selected');
                });
                this.classList.add('selected');
                
                updateProgress();
            });
        });

        function updateProgress() {
            const totalQuestions = 3;
            let answered = 0;
            
            for (let i = 1; i <= totalQuestions; i++) {
                if (document.querySelector(`input[name="q${i}"]:checked`)) {
                    answered++;
                }
            }
            
            progressValue = (answered / totalQuestions) * 100;
            document.getElementById('progressBar').style.width = progressValue + '%';
        }

        function checkAnswers() {
            let score = 0;
            const totalQuestions = Object.keys(answers).length;
            
            for (let question in answers) {
                const selected = document.querySelector(`input[name="${question}"]:checked`);
                const options = document.querySelectorAll(`input[name="${question}"]`);
                
                if (!selected) continue;
                
                options.forEach(option => {
                    const label = option.parentElement;
                    label.classList.remove('selected', 'correct', 'incorrect');
                    
                    if (option.value === answers[question]) {
                        label.classList.add('correct');
                    }
                    
                    if (option.checked && option.value !== answers[question]) {
                        label.classList.add('incorrect');
                    }
                });
                
                if (selected.value === answers[question]) {
                    score++;
                }
            }
            
            const resultDiv = document.getElementById('result');
            const percentage = (score / totalQuestions) * 100;
            
            if (percentage === 100) {
                resultDiv.className = 'result success';
                resultDiv.textContent = `🎉 Perfect! You got ${score}/${totalQuestions} correct!`;
            } else {
                resultDiv.className = 'result partial';
                resultDiv.textContent = `You got ${score}/${totalQuestions} correct. Review the material and try again!`;
            }
            
            document.getElementById('progressBar').style.width = '100%';
            
            document.querySelector('.submit-btn').disabled = true;
        }
    </script>
</body>
</html>
