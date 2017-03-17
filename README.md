Copy this to your Homestead installation directory, into the `scripts` folder.

Then in your Homestead.yaml config you can use it like the following example:

`
folders:
    - map: ~/path/to/your/silex/dir
      to: /home/vagrant/Code

sites:
    - map: silex.dev
      to: /home/vagrant/Code/web
      type: silex
`

Remember to change your hosts file to point to the domain you want ;)
