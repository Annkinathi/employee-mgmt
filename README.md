#creates  the div
var courseDetails = document.createElement('div')
    
    #creates div content
    var textContent = 'Course:' + courseName + " " + 'Name:' + studentName + " " + 'Lecture Hall:'  + lechallName;
    
    #adds content to the div
    courseDetails.textContent = textContent;
    
    #design the content
    courseDetails.classList.add('alert', 'alert-info')
    
    displays the div with the content
    document.getElementById('courses').appendChild(courseDetails)

    console.log(courseDetails)