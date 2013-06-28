utils
=====

A compiled list of tips/tricks repo.

* CLI for dictionary lookup (requires curl)

  ```bash
  dict() {
       curl dict://dict.org/d:$1
  }
  ```
  
  TODO: format output, add options for foldoc

* Delete lines in files using sed

   ```bash
   sed -i '<START>,<END>d' <FILENAME>
   ```

* 
