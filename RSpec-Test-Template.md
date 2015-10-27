**Rationale**

We have our own RSpec template for our project.

**Mechanism**

Navigate to: _Preferences > Editor > File and Code Templates_ and select _RSpec Test Template_ on the _Templates_ tab.

````
#parse("Ruby File Header.rb")
require "rails_helper"

RSpec.describe ${Behaviour_name} do

  it "should ${It_should}" do
    expect(true).to eq(true)
  end

end
````

 
