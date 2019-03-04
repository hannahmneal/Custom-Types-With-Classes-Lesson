# Custom-Types-With-Classes-Lesson

#Reading Notes
#Chapter 7: Custom Types with Classes

# Each C# app must provide its own, specific, custom Types to do the specific work of the application; The most common way to create custom types is by creating classes.

# ACCESSIBILITY LEVELS
# There are five main levels that can be applied to CLASSES, METHODS, PROPERTIES, and DATA MEMBERS:
#   public: accessible c/o restriction (e.g., defined in one .cs file, used in another)
#   private: cannot be called outside the class it's defined in, even by children
#      def - encapsulation: Storing private data only accessible inside the object
#   protected: unaccessible from outside class hierarchy/family (usable by children/fam)
#   internal: allow access from anywhere within the same compiled DLL (assembly)
#   protected internal: the only allowed combination of multiple access modifiers

# PROPERTIES
# Class props are the interface you provide to external code to get and modify the values of the private fields. Properties should have PUBLIC accessibility, unlike FIELDS, which are PRIVATE.

# METHODS
# The new function. Code blocks on a class that perform logic. They are the behaviors of your custom type.

# FIELDS
# Used to store values in an object. Usually private (unlike PROPS) and cannot be accessed outside the object wherein it is defined.

# CONSTRUCTOR
# Called when the class is instantiated. It's role is to ensure the new object is setup and ready for immediate use. In C#, the "new" keyword is how we call a constructor. If a construct. is not defined, it will be given a "default" construct. that accepts no params and does nothing.