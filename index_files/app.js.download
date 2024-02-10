// function setBackground() {
//     var textBackground = document.getElementById('text-area')
//     textBackground.style.backgroundImage = 'url(' + event.target.src + ')'
//     console.log(event.target.src)
// }
function textColor() {
    var textColor = document.getElementById('text-area')
    textColor.style.color = event.target.value
    // console.log(event.target.value)
}
function decoration() {
    var decoration = document.getElementById('text-area')
    var value = event.target.innerText
    //    console.log( event.target.innerText)
    if (value === "B") {
        if (decoration.style.fontWeight === "bold") {
            decoration.style.fontWeight = "normal"
            event.target.style.fontWeight = "normal"
        } else {
            decoration.style.fontWeight = "bold"
            event.target.style.fontWeight = "bold"
        }
    }
    if (value === "I") {
        if (decoration.style.fontStyle === "italic") {
            decoration.style.fontStyle = "normal"
            event.target.style.fontStyle = "normal"
        } else {
            decoration.style.fontStyle = "italic"
            event.target.style.fontStyle = "italic"
        }
    }

    if (value === "U") {
        if (decoration.style.textDecoration === "underline") {
            decoration.style.textDecoration = "none"
            event.target.style.textDecoration = "none"
        } else {
            decoration.style.textDecoration = "underline"
            event.target.style.textDecoration = "underline"
        }
    }
}

function changeTextSize() {
    var changeFontSize = document.getElementById("text-area")
    changeFontSize.style.fontSize = event.target.value + "px"
}
function setBackground() {
    var textBackground = document.getElementById('text-area')
    textBackground.style.backgroundImage = 'url(' + event.target.src + ')'

}
function backGroundColor() {
    var backGroundColor = document.getElementById("text-area")
    backGroundColor.style.backgroundColor = event.target.value;
    backGroundColor.style.backgroundImage = "none"
}
function post() {
    var post = document.getElementById("items")
    var area = document.getElementById("text-area")
    area.disabled = true
    post.style.display = "none"


}


