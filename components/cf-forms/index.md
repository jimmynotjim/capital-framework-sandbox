---
layout: default
title:  "cf-forms"
parent: "Components"
---

## Form labels

### Label header

<label class="form-label-header">
    Form label header
</label>


## Super input

## Example

<input class="input__super" type="text" value="Super input" title="Test input">
<button class="a-btn a-btn__super">Super</button>


## Input states

### Error state

<input class="error" type="text" value="Invalid input" title="Test input">

### Warning state

<input class="warning" type="text" value="Invalid input" title="Test input">

### Success state

<input class="success" type="text" value="Validated input" title="Test input">

### Disabled state

<input class="disabled" disabled="true" autocomplete="off" type="text" value="Validated input" title="Test input">

## Form icons

### Form input icons

<input type="text" value="" title="Test input">
<span class="cf-form_input-icon cf-icon cf-icon-email"></span>

### Form input error icon

<input class="error" type="text" value="Invalid input" title="Test input">
<span class="cf-form_input-icon cf-icon cf-icon-delete-round" role="alert"></span>

### Form input warning icon

<input class="warning" type="text" value="Invalid input" title="Test input">
<span class="cf-form_input-icon cf-icon cf-icon-error-round" role="alert"></span>

### Form input success icon

<input class="success" type="text" value="Validated input" title="Test input">
<span class="cf-form_input-icon cf-icon cf-icon-approved-round"></span>

## Form group

### Form group block

<div class="block">
    <div class="form-group">
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
    </div>
    <div class="form-group">
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
    </div>
    <div class="form-group">
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
    </div>
</div>

### Real world example
<div class="block">
    <div class="form-group">
        <label class="form-label-header">Form group</label>
        <div class="form-group_item">
            <input type="text" value="Form group item" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" value="Form group item" title="Test input">
        </div>
    </div>
    <div class="form-group">
        <label class="form-label-header">Form group</label>
        <div class="form-group_item">
            <input type="text" value="Form group item" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" value="Form group item" title="Test input">
        </div>
    </div>
</div>

## Input with button

### Default input and button

<div class="input-with-btn">
    <div class="input-with-btn_input">
        <input type="text" title="Test input">
    </div>
    <div class="input-with-btn_btn">
        <button class="a-btn">Search</button>
    </div>
</div>

### Super input and button

<div class="input-with-btn">
    <div class="input-with-btn_input">
        <input class="input__super" type="text" title="Test input">
    </div>
    <div class="input-with-btn_btn">
        <button class="a-btn a-btn__super">Search</button>
    </div>
</div>

## Button inside input

### Default button inside of an default input

<div class="block">
    <div class="btn-inside-input">
        <input type="text"
               value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable." title="Test input">
        <button class="a-btn a-btn__link">
            Clear
            <span class="cf-icon cf-icon-delete"></span>
        </button>
    </div>
</div>

### Super button inside of a super input

<div class="block">
    <div class="btn-inside-input">
        <input class="input__super"
               type="text"
               value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable." title="Test input">
        <button class="a-btn a-btn__super a-btn__link a-btn__secondary">
            Clear
            <span class="cf-icon cf-icon-delete"></span>
        </button>
    </div>
</div>
