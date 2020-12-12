# jetpack-compose-todo-app

[Compose for Desktop](https://www.jetbrains.com/lp/compose/) todo application

## Prerequisite

- Install and configure Android SDK Manager
- JDK11(jdk-11.0.9.1+1) or later
   - Note : EXCEPTION_ACCESS_VIOLATION occurred with jdk-11.0.8+10. Use the latest JDk11.
   
       ```
       Java frames: (J=compiled Java code, j=interpreted, Vv=VM code)
       j  sun.awt.windows.WComponentPeer._setFont(Ljava/awt/Font;)V+0 java.desktop@11.0.8
       j  sun.awt.windows.WComponentPeer.setFont(Ljava/awt/Font;)V+7 java.desktop@11.0.8
       j  sun.awt.windows.WWindowPeer.initialize()V+42 java.desktop@11.0.8
       j  sun.awt.windows.WFramePeer.initialize()V+1 java.desktop@11.0.8
       j  sun.awt.windows.WComponentPeer.<init>(Ljava/awt/Component;)V+83 java.desktop@11.0.8
       j  sun.awt.windows.WCanvasPeer.<init>(Ljava/awt/Component;)V+2 java.desktop@11.0.8
       j  sun.awt.windows.WPanelPeer.<init>(Ljava/awt/Component;)V+2 java.desktop@11.0.8
       j  sun.awt.windows.WWindowPeer.<init>(Ljava/awt/Window;)V+2 java.desktop@11.0.8
       j  sun.awt.windows.WFramePeer.<init>(Ljava/awt/Frame;)V+2 java.desktop@11.0.8
       j  sun.awt.windows.WToolkit.createFrame(Ljava/awt/Frame;)Ljava/awt/peer/FramePeer;+5 java.desktop@11.0.8
       j  java.awt.Frame.addNotify()V+20 java.desktop@11.0.8
       j  java.awt.Window.show()V+8 java.desktop@11.0.8
       j  java.awt.Component.show(Z)V+5 java.desktop@11.0.8
       j  java.awt.Component.setVisible(Z)V+2 java.desktop@11.0.8
       j  java.awt.Window.setVisible(Z)V+2 java.desktop@11.0.8
       j  androidx.compose.desktop.ComposeWindow.setVisible(Z)V+10
       j  androidx.compose.desktop.AppWindow.show(Lkotlin/jvm/functions/Function2;)V+63
       j  androidx.compose.desktop.AppWindowKt$Window$1.run()V+64
       j  java.awt.event.InvocationEvent.dispatch()V+47 java.desktop@11.0.8
       j  java.awt.EventQueue.dispatchEventImpl(Ljava/awt/AWTEvent;Ljava/lang/Object;)V+21 java.desktop@11.0.8
       j  java.awt.EventQueue$4.run()Ljava/lang/Void;+32 java.desktop@11.0.8
       j  java.awt.EventQueue$4.run()Ljava/lang/Object;+1 java.desktop@11.0.8
       v  ~StubRoutines::call_stub
       j  java.security.AccessController.doPrivileged(Ljava/security/PrivilegedAction;Ljava/security/AccessControlContext;)Ljava/lang/Object;+0 java.base@11.0.8
       j  java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(Ljava/security/PrivilegedAction;Ljava/security/AccessControlContext;Ljava/security/AccessControlContext;)Ljava/lang/Object;+18 java.base@11.0.8
       j  java.awt.EventQueue.dispatchEvent(Ljava/awt/AWTEvent;)V+46 java.desktop@11.0.8
       j  java.awt.EventDispatchThread.pumpOneEventForFilters(I)V+78 java.desktop@11.0.8
       j  java.awt.EventDispatchThread.pumpEventsForFilter(ILjava/awt/Conditional;Ljava/awt/EventFilter;)V+35 java.desktop@11.0.8
       j  java.awt.EventDispatchThread.pumpEventsForHierarchy(ILjava/awt/Conditional;Ljava/awt/Component;)V+11 java.desktop@11.0.8
       j  java.awt.EventDispatchThread.pumpEvents(ILjava/awt/Conditional;)V+4 java.desktop@11.0.8
       j  java.awt.EventDispatchThread.pumpEvents(Ljava/awt/Conditional;)V+3 java.desktop@11.0.8
       j  java.awt.EventDispatchThread.run()V+9 java.desktop@11.0.8
       v  ~StubRoutines::call_stub
       
       siginfo: EXCEPTION_ACCESS_VIOLATION (0xc0000005), reading address 0x0000000000000058
       ``` 

## Reference

https://github.com/JetBrains/compose-jb/blob/master/tutorials/Getting_Started/README.md


https://github.com/JetBrains/compose-jb/tree/master/templates/multiplatform-template
