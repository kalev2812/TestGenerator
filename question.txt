const quizData = [
    {
        question: "Software is defined as ___________",
        a: "set of programs, documentation & configuration of data",
        b: "set of programs",
        c: "documentation and configuration of data",
        d: "None of the mentioned",
        correct: "a",
    },
    {
        question: "What is Software Engineering?",
        a: "Designing a software ",
        b: "Testing a software ",
        c: "Application of engineering principles to the design a software ",
        d: "None of the above ",
        correct: "c",
    },
    {
        question: "Who is the father of Software Engineering?",
        a: "Margaret Hamilton ",
        b: "Watts S. Humphrey ",
        c: "Alan Turing ",
        d: "Boris Beizer ",
        correct: "b",
    },
    {
        question: "What are the features of Software Code?",
        a: "Simplicity ",
        b: "Accessibility ",
        c: "Modularity ",
        d: "All of the above ",
        correct: "c",
    },
    {
        question: " ____________ is a software development activity that is not a part of software processes.",
        a: "Validation ",
        b: "Specification ",
        c: "Development ",
        d: "Dependence ",
        correct: "d",
    },
    {
        question: "Define Agile scrum methodology.",
        a: "project management that emphasizes incremental progress ",
        b: "project management that emphasizes decremental progress ",
        c: "project management that emphasizes neutral progress ",
        d: "project management that emphasizes no progress ",
        correct: "",
    },
    {
        question: "________ is primarily a personal activty , mostly done as an individual",
        a: "Software engineering ",
        b: "Programming ",
        c: "Testing ",
        d: "Softeare development  ",
        correct: "a",
    },
    {
        question: "The role of SOftware and COmputer Programmer is _______",
        a: "Changeble  ",
        b: "Not changeble ",
        c: "Interchangeable ",
        d: "Not interchangeable ",
        correct: "d",
    },
    {
        question: "Tracking ________ helps you develop a holistic view of a development process",
        a: "Productivity ",
        b: "measuring ",
        c: "efficiency ",
        d: "scale ",
        correct: "c",
    },
    {
        question: "______ is used to help organization in effectively determining cause of problems that occurred.",
        a: "program ",
        b: "data ",
        c: "software ",
        d: "development ",
        correct: "b",
    },
    {
        question: "________ are used to speed up input and output processes in machine",
        a: "Programs ",
        b: "data ",
        c: "software ",
        d: "Development ",
        correct: "a",
    },
    {
        question: "With programming in the _______, coding managers place emphasis on partitioning work into modules with precisely-specified interactions.",
        a: "large ",
        b: "small ",
        c: "all of above ",
        d: "None of the above ",
        correct: "a",
    },
    {
        question: "Programming in the large requires _______ skills",
        a: "abstraction-creating ",
        b: "management ",
        c: "all of above ",
        d: "None of the above ",
        correct: "c",
    },
    {
        question: "_______ is a software development tool that allows you to build an application without coding",
        a: "Low code platform",
        b: "No-code platform ",
        c: "Both a and b ",
        d: "NOne of above ",
        correct: "b",
    },
    {
        question: "_______ is a full-stack development environment with drag-and-drop capabilities to create software without coding knowledge",
        a: "Low-code ",
        b: "No code ",
        c: "Software ",
        d: "Development ",
        correct: "a",
    },
    /*{
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
    {
        question: "",
        a: " ",
        b: " ",
        c: " ",
        d: " ",
        correct: "",
    },
*/

    
];

const quiz = document.getElementById('quiz')
const answerEls = document.querySelectorAll('.answer')
const questionEl = document.getElementById('question')
const a_text = document.getElementById('a_text')
const b_text = document.getElementById('b_text')
const c_text = document.getElementById('c_text')
const d_text = document.getElementById('d_text')
const submitBtn = document.getElementById('submit')

let currentQuiz = 0
let score = 0

loadQuiz()

function loadQuiz() {
    deselectAnswers()

    const currentQuizData = quizData[currentQuiz]

    questionEl.innerText = currentQuizData.question
    a_text.innerText = currentQuizData.a
    b_text.innerText = currentQuizData.b
    c_text.innerText = currentQuizData.c
    d_text.innerText = currentQuizData.d
}

function deselectAnswers() {
    answerEls.forEach(answerEl => answerEl.checked = false)
}

function getSelected() {
    let answer

    answerEls.forEach(answerEl => {
        if(answerEl.checked) {
            answer = answerEl.id
        }
    })

    return answer
}

submitBtn.addEventListener('click', () => {
    const answer = getSelected()
    
    if(answer) {
        if(answer === quizData[currentQuiz].correct) {
            score++
        }

        currentQuiz++

        if(currentQuiz < quizData.length) {
            loadQuiz()
        } else {
            quiz.innerHTML = `
                <h2>You answered ${score}/${quizData.length} questions correctly</h2>

                <button onclick="location.reload()">Reload</button>
            `
        }
    }
})