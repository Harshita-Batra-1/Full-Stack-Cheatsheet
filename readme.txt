##React
Basic components (button, input, form, etc.)
Buttons
<Button> - A basic button component.
<Button type="primary"> - A primary button with a higher visual weight.
<Button type="dashed"> - A dashed button with a lower visual weight.
<Button type="danger"> - A button with a red background color, used for dangerous actions.
<Button shape="circle"> - A circular button.
<Button size="large"> - A large button.
<Button size="small"> - A small button.
<Button loading> - A button with a loading spinner.
<Button block> - A button that spans the full width of its parent container.
<Button disabled> - A disabled button.
<Button href="url"> - A button that acts as a link.
<Button icon={<Icon type="edit" />}> - A button with an icon.
Inputs
<Input> - A basic input field.
<Input type="password"> - A password input field.
<Input prefix={<Icon type="user" />}> - An input field with a prefix icon.
<Input suffix={<Icon type="search" />}> - An input field with a suffix icon.
<Input.TextArea> - A textarea input field.
<Input.Search> - An input field with a search icon.
Form
<Form> - A basic form container.
<Form.Item> - A form item, used to wrap form controls.
<Form.Item label="Name"> - A form item with a label.
<Form.Item hasFeedback> - A form item with validation feedback.
<Form.Item help="Some help text"> - A form item with help text.
<Form.Item validateStatus="success"> - A form item with a success validation status.
<Form.Item validateStatus="warning"> - A form item with a warning validation status.
<Form.Item validateStatus="error"> - A form item with an error validation status.
<Form.Item labelCol={{ span: 8 }} wrapperCol={{ span: 16 }}> - A form item with customized label and wrapper column spans.
<Form.List name="names"> - A dynamic form list.
