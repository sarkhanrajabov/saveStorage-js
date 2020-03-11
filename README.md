# saveStorage

> saveStorage is a lightweight javascript plugin that automatically stores and recovers form values to prevent losing data when editing an HTML form.

## Supported elements:

- input (text,number,email,password...)
- radio, checkbox (input)
- select
- textarea

## Usage:

Include saveStorage JS file

```
<script src="savestorage.min.js"></script>
```

HTML

```
<form id="myform"> // id required
  <div>
    <label>Name</label>
    <input type="text" name="name">
  </div>
  <div>
    <label>Surname</label>
    <input type="text" name="surname">
  </div>
</form>
```

initialize saveStorage

```
saveStorage('#myform');
```

## Options:

```
saveStorage('#myform', {
    exclude: ['passowrd','hidden'] // does not save input types
});
```
