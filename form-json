function formJsonString( form ) {
  var obj = {};
  var elements = form.querySelectorAll( "input, select, textarea" );
  elements.forEach(element => {
    let name = element.name
    let value = element.value
    if(name){
      obj[name] = value
    }
  })
  return JSON.stringify( obj );
}
