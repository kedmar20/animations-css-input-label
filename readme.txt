
.form input:focus + .label-name {
/* plus works only when the second teil element is BELOW the first element */
every time we focus on the input we are affecting the label (.label-name)

span is inside label - we can easily styling only text without whole label

input:valid // it's added the required on input field = when this is valid, so when there is something e.g. 'text'



also something strange:
that works: .form label::after {
that don't: .form input:valid + .form label::after {
    and must be replace trough this: .form input:valid + .label-name::after {

    