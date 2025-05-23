<!-- This file was automatic generated. Do not edit it manually -->

<PropsTable :data="[
  {
    'name': 'as',
    'description': '<p>The element or component this component should render as. Can be overwritten by <code>asChild</code>.</p>\n',
    'type': 'AsTag | Component',
    'required': false,
    'default': '\'div\''
  },
  {
    'name': 'asChild',
    'description': '<p>Change the default rendered element for the one passed as a child, merging their props and behavior.</p>\n<p>Read our <a href=\'https://www.radix-vue.com/guides/composition.html\'>Composition</a> guide for more details.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'defaultValue',
    'description': '',
    'type': 'number',
    'required': false
  },
  {
    'name': 'disabled',
    'description': '<p>When <code>true</code>, prevents the user from interacting with the Number Field.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'formatOptions',
    'description': '<p>Formatting options for the value displayed in the number field. This also affects what characters are allowed to be typed by the user.</p>\n',
    'type': 'NumberFormatOptions',
    'required': false
  },
  {
    'name': 'id',
    'description': '<p>Id of the element</p>\n',
    'type': 'string',
    'required': false
  },
  {
    'name': 'locale',
    'description': '<p>The locale to use for formatting dates</p>\n',
    'type': 'string',
    'required': false,
    'default': '\'en-US\''
  },
  {
    'name': 'max',
    'description': '<p>The largest value allowed for the input.</p>\n',
    'type': 'number',
    'required': false
  },
  {
    'name': 'min',
    'description': '<p>The smallest value allowed for the input.</p>\n',
    'type': 'number',
    'required': false
  },
  {
    'name': 'modelValue',
    'description': '',
    'type': 'number',
    'required': false
  },
  {
    'name': 'name',
    'description': '<p>The name of the number field. Submitted with its owning form as part of a name/value pair.</p>\n',
    'type': 'string',
    'required': false
  },
  {
    'name': 'required',
    'description': '<p>When <code>true</code>, indicates that the user must set the value before the owning form can be submitted.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'step',
    'description': '<p>The amount that the input value changes with each increment or decrement &quot;tick&quot;.</p>\n',
    'type': 'number',
    'required': false,
    'default': '1'
  }
]" />

<EmitsTable :data="[
  {
    'name': 'update:modelValue',
    'description': '<p>Event handler called when the value changes.</p>\n',
    'type': '[val: number]'
  }
]" />

<SlotsTable :data="[
  {
    'name': 'modelValue',
    'description': '',
    'type': 'number'
  },
  {
    'name': 'textValue',
    'description': '',
    'type': 'string'
  }
]" />
