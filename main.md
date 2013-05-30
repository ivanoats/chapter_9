!SLIDE

# accepts_nested_attributes_for

- a model method
- Defines an attributes writer for the specified association(s).
- rails 3, you also need:

`attr_accessible :nestedmodel_attributes`

!SLIDE incremental
## exists?, ActiveRecord::FinderMethods

returns true if a record exists in a table that matches the id or conditions given
http://api.rubyonrails.org/classes/ActiveRecord/FinderMethods.html#method-i-exists-3F

## exists?, Paperclip::Storage::Filesystem
returns true if the attached file exists
